# Visor de Datos para Desarrollo de Energia Renovable de Colombia
**➡️ Demo en línea:** [Ver el visor en GitHub Pages](https://sxdesx.github.io/ReniovablesCOL)
---
## Descripción
Este visor web permite explorar de manera interactiva la infraestructura eléctrica y variables clave para la planeación energética en Colombia.  
Está desarrollado con **Leaflet.js**, integrando capas en formatos **GeoJSON** y servicios **WMS/ArcGIS**, junto con un **sidebar dinámico** que muestra:
---
## Funcionalidades principales
- ⚡ **Capas de generación actual**: solares, eólicas e hidroeléctricas.
- 🔌 **Red eléctrica y subestaciones**.
- 🌱 **Restricciones ambientales y sociales** (RUNAP, Zonas de Reserva Campesina, comunidades indígenas y negras, restitución de tierras, etc.).
- ☀️ **Condiciones del terreno** (pendientes IGAC vía WMS, radiación solar multianual ArcGIS).
- 🖱️ **Interactividad**: Activar/desactivar capas con control agrupado,Popup con atributos de cada entidad, Sidebar dinámico con nombre, fuente y leyenda de cada capa activa.
- ✏️ **Herramientas de dibujo** (líneas, polígonos) con cálculo automático de áreas y distancias.

## Estructura del proyecto
├── index.html # Página principal del visor
├── js/
│ └── app.js # Lógica principal en JavaScript
├── assets/
│ ├── css/
│ │ ├── style.css # Estilos del visor
│ │ └── images/ # Íconos y leyendas
│ └── css/images/legend/ # Leyendas (.png) por capa
├── data/
│ └── *.geojson # Capas locales en GeoJSON
└── README.md # Este archivo

Las capas utilizadas provienen de diferentes instituciones y servicios abiertos:

- **IGAC** – Pendientes de Colombia (WMS).  
- **ArcGIS Online** – Radiación Solar Multianual.  
- **PNN – RUNAP** (Registro Único de Áreas Protegidas).  
- **ANT, MinInterior, URT** – Zonas de Reserva Campesina, Comunidades Negras, Resguardos Indígenas y Restitución de Tierras.  
- **OSM** – Generación eléctrica, subestaciones y líneas de transmisión.

Autor

Desarrollado por sxdesx.
Contacto: sandra.defex@gmail.com

