# Dashboard Interactivo de Ventas en Excel 📊

Una solución integral de Inteligencia de Negocios desarrollada en Microsoft Excel para analizar el rendimiento comercial anual por colaboradores, categorías de productos y distribución geográfica en República Dominicana.

---

## 🌟 Características Principales

* **Indicador Dinámico en Tiempo Real:** Muestra automáticamente el vendedor con la venta mensual más alta del periodo seleccionado (ej. *Juan Pérez – $5,067,400.00 en Diciembre*).
* **Top 3 Destacado Automático:** Reglas avanzadas de Formato Condicional para resaltar dinámicamente en verde a los 3 mejores vendedores.
* **Filtrado Multidimensional:** Segmentadores de datos (Slicers) interconectados por Mes, Empleado, Producto y Ciudad que actualizan sincrónicamente todos los gráficos y métricas del reporte.
* **Segmentación Geográfica y por Categoría:** Desglose visual de ventas por provincias/ciudades (Santo Domingo, Santiago, San Cristóbal, La Vega, San Pedro de Macorís) y por línea de negocio (Tecnología vs. Hogar).
* **Detalle Operativo con Alertas:** Formato condicional automatizado que resalta las transacciones diarias que superan el promedio de ventas (>$28,613).
* **Interfaz de Modo Oscuro:** Diseño profesional ejecutivo optimizado para una lectura clara y moderna.

---

## 🛠️ Herramientas y Técnicas de Excel Utilizadas

* **Microsoft Excel (Office 365 / 2016+)**
* **Tablas Dinámicas y Gráficos Dinámicos:** Consolidación de datos multidimensionales y arquitectura de datos backend.
* **Segmentadores de Datos (Slicers):** Filtros interactivos vinculados entre múltiples tablas para exploración de datos a varios niveles.
* **Formato Condicional Avanzado:** Reglas dinámicas basadas en fórmulas para resaltado del Top N y alertas transaccionales.
* **Formato de Números y Fórmulas:** Cálculo de KPIs y formato de moneda personalizado.

---

## 📂 Estructura del Libro de Trabajo

* `Dashboard`: Panel de control ejecutivo principal e interactivo con métricas y gráficos en tiempo real.
* `Pivot (Empresa)` & `Pivot (Empleados)`: Arquitectura de datos backend y resúmenes consolidados.
* `Filtro 1`: Detalle de registro transaccional con alertas automatizadas.
* `DataBase Ventas 2025`: Base de datos cruda con el histórico de ventas.

---

## 🚀 Cómo Usarlo

1. Clona o descarga este repositorio.
2. Abre el archivo `.xlsx` en Microsoft Excel (se recomienda versión 2016 o superior).
3. Navega a la pestaña `Dashboard` e interactúa con los **Slicers** (Mes, Producto, Empleado, Ciudad) para filtrar las métricas dinámicamente.
