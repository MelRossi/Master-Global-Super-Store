# Master-Global-Super-Store
# 📊 Proyecto Integrador M1 – Global Super Store  
### "Descifrando la operación empresarial"  
**Autora:** Melisa Rossi | **Curso:** Data Analytics – Henry  

---

## 📝 Descripción del Proyecto

Este proyecto forma parte del Módulo 1 del programa de Data Analytics en Henry.  
El objetivo principal fue analizar un conjunto de datos de **Global Super Store**, que contiene información de ventas, clientes, productos, envíos y ganancias a nivel global durante los años **2013 y 2014**.

El trabajo incluye:

- Procesos completos de **ETL**  
- Limpieza y normalización de datos  
- Construcción de métricas y KPIs  
- Análisis exploratorio y visual  
- Identificación de patrones clave  
- Construcción de dashboards  

---

## 🎯 Objetivos del Proyecto

✔ Desarrollar procesos de **ETL** adecuados y reproducibles  
✔ Aplicar **análisis exploratorio de datos (EDA)**  
✔ Detectar patrones, relaciones e inconsistencias  
✔ Construir métricas relevantes y KPIs  
✔ Crear visualizaciones y dashboards  
✔ Elaborar conclusiones claras orientadas al cliente  

---

## 📂 Datos Utilizados

Se trabajó con dos archivos principales:

- **Master Global Super Store** → Ventas, clientes, envíos, ganancias, costos  
- **Products Global Super Store** → Detalle de productos y categorías  

Ambos datasets fueron integrados y analizados para extraer información significativa.

---

## 🧹 Limpieza y Preparación de Datos (ETL)

Se aplicaron los siguientes pasos:

### 🔍 **1. Eliminación de registros vacíos**
- Se identificaron 17 filas sin información, que fueron eliminadas.

### 🧽 **2. Depuración de columnas irrelevantes**
- Eliminación de columnas: `Columna1`, `Columna2`, `Records` y `Customer`  
  (redundantes o sin valor analítico).

### 📦 **3. Verificación de duplicados**
- Se utilizó `COUNTIFS()` confirmando que **no existían duplicados**.

### 📅 **4. Validación de fechas**
- Se comprobó que `Sales Date` y `Order Date` eran idénticas.  
- Se conservó únicamente **Order Date**.

### 🕒 **5. Filtrado temporal**
- Se seleccionaron los registros del período **2013–2014**.

### 🚢 **6. Normalización del Shipping Cost**
- Se detectaron **outliers extremos** (hasta USD 3.49 millones).  
- Se aplicó un límite razonable reemplazando valores por encima del rango normal.

---

## 🔎 Análisis Exploratorio (EDA)

Se realizó un EDA para comprender la estructura del dataset y detectar tendencias:

### Métodos utilizados:
- Estadísticas descriptivas  
- Tablas dinámicas  
- Segmentación por categoría, región, mercado, prioridad y método de envío  
- Visualizaciones interactivas (barras, líneas, tortas)

### Segmentos analizados:
- Ventas por **categoría**  
- Ventas por **subcategoría**  
- Ventas por **mercado**  
- Ventas por **región**  
- Ventas por **método de envío**  
- Ventas por **prioridad del pedido**  
- Ventas por **segmento de cliente**  

---

## 💡 Insights Principales

### ⭐ 1. Categoría con mayor volumen de ventas
**Office Supplies** lidera las ventas con USD 209.9M.

### ⭐ 2. Año más rentable
**2014** supera a 2013 en ventas, alcanzando USD 252.7M.  
Implica crecimiento y mayor rentabilidad.

### ⭐ 3. Mercado más relevante
**LATAM** encabeza con USD 187M en ventas.  
En regiones, **Central** es la más fuerte (USD 108.8M).

### ⭐ 4. Método de envío predominante
**Standard Class** → más del 50% de las órdenes.  
Los clientes priorizan costos sobre velocidad.

### ⭐ 5. Prioridad más frecuente
**Medium** representa más de la mitad de los pedidos.

### ⭐ 6. Segmento de clientes más importante
**Consumer** → 51.7% de las ventas totales.

---

## 📈 KPIs & Métricas

Algunos indicadores clave:

- **Total de ventas por categoría**  
- **Total de ventas por mercado y región**  
- **Ganancia por año**  
- **Costo total de envío**  
- **Distribución por método de envío**  
- **Participación por segmento de cliente**  

---

## 📊 Dashboard

Se desarrollaron visualizaciones interactivas que permiten:

- Comparar categorías, regiones, mercados  
- Analizar la evolución temporal  
- Evaluar costos, ganancias y segmentos  
- Explorar insights con filtros dinámicos  

---

## 🧩 Conclusiones

El análisis permitió identificar patrones claros de comportamiento comercial:

- La empresa presenta una fuerte **dependencia de LATAM** y del segmento **Consumer**.  
- La categoría **Office Supplies** sostiene gran parte de la facturación.  
- El método **Standard Class** domina ampliamente las preferencias de los clientes.  
- Existe un crecimiento significativo en ventas del 2013 al 2014.  

El proyecto demuestra la importancia de los procesos ETL y del análisis exploratorio para obtener una visión estratégica del negocio.

---

## 📬 Contacto

💼 **Melisa Rossi**  
📧 *[melirossi.mr@gmail.com]*  
🔗 GitHub: *[MelRossi]*  
🔗 LinkedIn: *[[tu perfil](https://www.linkedin.com/in/melisa-rossi-lagger/)]*

---

