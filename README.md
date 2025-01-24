# 📊 Dashboard-Potenciar-Solidario

## 📝 Descripción
El presente trabajo se basa en datos proporcionados por Guayerd, pertenecientes a la **ONG Potenciar Solidario**, los cuales han sido modificados para mantener la privacidad de la ONG.  
El objetivo es proporcionar una visión detallada y comprensible de los flujos de dinero de la organización, facilitando la identificación de tendencias, patrones y posibles áreas de mejora a través de gráficos interactivos y resúmenes financieros.

El dashboard cuenta con dos secciones principales:
- **Análisis Monetario**: Esta sección ofrece un panorama completo del flujo de dinero, incluyendo ingresos, egresos y una comparativa general. Es ideal para obtener una comprensión rápida y detallada del estado financiero de la ONG.
- **Análisis Individual**: En esta sección, se desglosa la información financiera por individuos, permitiendo un análisis detallado de donadores y proveedores.

## 💻 Tecnologías utilizadas
- Google Sheets
- Looker Studio

## 🛠 Trabajo realizado
- **ETL**: Se realizó un proceso de limpieza, extracción y transformación de los datos, ya que estos se encontraban en distintos formatos (csv, excel y word), con errores ortográficos, datos incorrectos y duplicados.
- **Normalización**: Además de los problemas anteriores, los datos no estaban bien organizados, ya que había redundancia. Los datos fueron normalizados hasta la 3ra forma normal.
- **Visualización de datos**: Una vez que los datos estaban limpios, se conectó Looker Studio a los datos procesados para crear campos calculados, gráficos y segmentadores interactivos.

## 📁 Estructura del proyecto
- `datos iniciales/`: Contiene los datos en su forma original, separados en **Ingresos**, **Proveedores (egresos)** y los **detalles**.
- `datos transformados/`: Contiene los datos en un archivo Excel unificado. Este archivo es solo para referencia, ya que el archivo original (y el que utiliza el dashboard) está en **Google Sheets**, y se puede acceder a través del siguiente enlace:  
  [Fuente de datos en Sheets](https://docs.google.com/spreadsheets/d/1azdLl39lNJlQIusHZmuMCipZguuZ5G3GWoFEs6CZP_Y/edit?gid=0#gid=0)
- `estructura bd/`: Contiene dos imágenes:  
  - **BD - Original**: Muestra cómo estaban estructurados los datos antes de normalizarlos.
  - **BD - Normalizada**: Muestra cómo quedaron organizados después de la normalización.

## 📈 Resultado Final
A continuación se adjunta el link a Looker Studio para acceder al dashboard:  
[Acceder al Dashboard](http://lookerstudio.google.com/reporting/1e69ca48-ee89-4e08-834c-8431f050a334)
