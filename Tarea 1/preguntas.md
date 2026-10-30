#  Análisis y Diseño de Requerimientos - AdventureWorks Cycles

## 1. Selección y Análisis de Decisiones

* **Decisión D2:** Lanzar una oferta especial para un producto[cite: 155].
  * *Descripción:* Implementar campañas de rebajas o descuentos promocionales en artículos seleccionados para estimular su rotación comercial.
  * *Objetivo empresarial:* Contribuir al incremento de los ingresos y maximizar el margen de ganancia global[cite: 154, 155].
  
* **Decisión D6:** Incrementar precios[cite: 155].
  * *Descripción:* Ajustar al alza el valor de venta de los productos en el mercado para optimizar la rentabilidad por unidad vendida.
  * *Objetivo empresarial:* Mejorar directamente los márgenes de ganancia frente a los costos de producción[cite: 154, 155].

---

## 2. Preguntas de Negocio

### Para la Decisión D2 (Ofertas especiales):
1. ¿Cómo ha variado la demanda total y las unidades vendidas de un producto antes, durante y después de aplicar la oferta especial?
2. ¿Cuál es el impacto de la oferta especial en el margen de ganancia total de la categoría del producto afectado?
3. ¿Qué tipos de ofertas especiales (descuentos por volumen, rebajas estacionales) generan mayores ingresos mensuales?

### Para la Decisión D6 (Incremento de precios):
1. ¿Cómo ha afectado el incremento de precios al volumen de ventas mensuales y a los ingresos totales de la compañía?
2. ¿Cuál es el margen de ganancia real obtenido por producto tras aplicar la subida de precios frente a su costo estándar de fabricación?
3. ¿En qué regiones geográficas o territorios el incremento de precios ha provocado una caída en la demanda cubierta?

---

## 3. Indicadores de Desempeño (KPIs)

* **Ventas Mensuales:** Suma de las cantidades ordenadas en un período mensual[cite: 55, 63].
* **Ingresos Mensuales:** Suma del producto entre el precio unitario y la cantidad vendida ($SUM(UnitPrice \times OrderQty)$)[cite: 63].
* **Margen de Ganancia:** Suma de la diferencia entre el precio unitario de venta y el costo estándar, multiplicada por la cantidad vendida ($SUM((UnitPrice - StandardCost) \times OrderQty)$)[cite: 64, 66].
* **Demanda Cubierta:** Relación entre los productos vendidos y la demanda total solicitada por los clientes[cite: 55].

---

## 4. Parámetros y Filtros de Análisis

Para que los directivos puedan explotar la información de forma dinámica, se establecen los siguientes parámetros:
* **Período de tiempo:** Años, meses y días (para evaluar el antes y después de la oferta o cambio de precio)[cite: 68].
* **Producto / Categoría:** Identificación específica de las bicicletas, accesorios o componentes afectados[cite: 64].
* **Territorio / Región:** Localización geográfica del cliente o mercado (América del Norte, Europa, Australia)[cite: 48].
* **Tipo de Promoción:** Identificador de la oferta especial aplicada[cite: 63].