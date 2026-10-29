# 🏷️ Sistema Automatizado de Generación de Etiquetas de Bodega


**Herramienta in-house para la estandarización visual y generación dinámica de rotulados, vinculada directamente al maestro de artículos del ERP.**

### 🎯 El Desafío Operativo
El rotulado de estanterías, ubicaciones (layout) y productos individuales se realizaba de forma manual. Esto generaba pérdida de horas operativas, discrepancias visuales en los códigos, errores de digitación y lentitud al momento de ejecutar los procesos de recepción, picking y auditorías físicas.

### 🚀 La Solución y Resultados
Desarrollé un generador centralizado que estandariza la identidad visual y operativa de la bodega:
* **Generación en 1 Clic:** Creación automática de etiquetas con códigos de barras/QR y descripciones exactas extraídas de la base de datos maestra.
* **Estandarización del Layout:** Formatos predefinidos para ubicaciones de rack, cajas de preparación y productos unitarios.
* **Ahorro de Tiempo:** Reducción del tiempo de rotulado de horas a minutos, eliminando el trabajo de diseño y ajuste manual de tamaños.
* **Precisión Operativa:** Reducción de errores humanos en la lectura de códigos durante el picking y la toma de inventarios.

### 🛠️ Stack Tecnológico
* **Frontend y Maquetación:** HTML5, CSS3 (Optimizado para formatos de impresión y medidas exactas de etiquetas), Vanilla JavaScript.
* **Integración de Códigos:** Librerías JS para la renderización dinámica de códigos de barras.
* **Backend:** Google Apps Script y conexión de base de datos para la extracción de códigos SKU y descripciones.

# 📋 App de Toma de Inventario y Auditorías Cíclicas


**Plataforma digital para la ejecución de conteos físicos en terreno, conciliación de stock y control de mermas sin uso de papel.**

### 🎯 El Desafío Operativo
Los inventarios físicos generales y cíclicos dependían de planillas impresas, conteos a mano y posterior doble digitación en el sistema. Este proceso era propenso a errores de transcripción, demoraba la detección de diferencias y extendía los tiempos de congelamiento de la bodega.

### 🚀 La Solución y Resultados
* **Conteo Digital en Terreno:** Interfaz responsiva (móvil/tablet) para ingresar las cantidades físicas contadas directamente frente al rack.
* **Conciliación Inmediata:** Cruce automático entre el conteo físico y el stock teórico del sistema, levantando alertas inmediatas sobre mermas o sobrantes.
* **Eliminación de Doble Digitación:** Supresión total del papel en el proceso de auditoría y cuadratura.
* **Trazabilidad:** Registro exacto de qué operador realizó el conteo, en qué fecha, hora y ubicación.

### 🛠️ Stack Tecnológico
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (Diseño responsivo y táctil).
* **Backend:** Google Apps Script.
* **Almacenamiento y Reportes:** Google Sheets como base de datos de auditoría.

