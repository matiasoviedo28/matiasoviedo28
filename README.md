## Matías Oviedo 👋

### Backend Developer / Builder

Construyo cosas útiles de punta a punta: backend, APIs, bases de datos, automatización e infraestructura. Si hay que tocar el servidor, escribir el código y dejarlo corriendo en producción, ese es mi terreno.

- 💳 **Backend Developer** en una fintech
- 🧑‍🚒 Fundador de **[bomberos.ar](https://bomberos.ar)**, plataforma para modernizar la gestión de cuarteles de bomberos voluntarios
- 🌐 Vengo del mundo **ISP / redes** (FTTH, VoIP, infraestructura), así que me siento cómodo donde se cruzan software, datos y redes

---

### 🛠️ Stack

**Lenguajes y frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-0C4B33?style=for-the-badge&logo=django&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

**Infraestructura y herramientas**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 🚀 Proyectos destacados

#### 🧑‍🚒 [bomberos.ar](https://bomberos.ar) — Fundador

Plataforma para modernizar la gestión de cuarteles de bomberos voluntarios. Nació de un problema real que conozco de primera mano.

- Control horario con **carga automática al registro único nacional (RUBA)**
- Legajos virtuales y múltiples perfiles con login para gestión de datos personales
- Arquitectura multi-asociación a nivel de base de datos
- Stack: Python · PostgreSQL · Linux · servidor dedicado

📄 *Documentación y arquitectura:* [REPOSITORIO](https://github.com/matiasoviedo28/bomberos.ar)

#### 🔥 [fwi](https://github.com/matiasoviedo28/FWI) — Prevención de incendios forestales

Sistema que calcula el **Fire Weather Index** sobre todo el territorio argentino a partir de los pronósticos del SMN, para monitorear el riesgo de incendio actual y pronosticado hasta **+72 h**.

- Procesa archivos **NetCDF** del modelo WRF del SMN sobre la grilla nativa de **4 km** (~167k puntos sobre Argentina)
- Índices de peligrosidad (FWI canadiense / CFFDRS) calculados con **xclim**, validados contra el estándar científico y corregidos para el **Hemisferio Sur**
- Extracción geoespacial **vectorizada (KDTree)** — de minutos a ~1 s por día
- **API FastAPI + PostgreSQL** y mapa web interactivo (isobandas vectoriales sobre Leaflet), todo **dockerizado**

📄 *Documentación y arquitectura:* [REPOSITORIO](https://github.com/matiasoviedo28/FWI)

#### 📡 [RadioLocal-VHF-HF](https://github.com/matiasoviedo28/RadioLocal-VHF-HF) — Planificación de cobertura de radio frecuencia

Herramienta **local** para planificar la cobertura de radio **VHF** en operativos, calculada sobre relieve real y corriendo 100% en tu propia máquina, sin depender de servicios web de terceros al momento de calcular.

- Cálculo de propagación con **Signal-Server** (modelo **Longley-Rice / ITM**) sobre relieve real, ejecutado íntegramente en el backend local
- Relieve **(DEM) Copernicus GLO-30** descargado on-demand desde el **bucket público en AWS** (sin API key) y **cacheado por tiles** como COG para trabajar offline
- **Descarga masiva por región** (CLI reanudable) para llevar una provincia o el país entero a operativos sin conectividad
- **Mapa interactivo** con **MapLibre GL JS** + *hillshade* y exportación a **Google Earth (KMZ)**; backend **FastAPI** y frontend, todo **dockerizado**

📄 *Documentación y arquitectura:* [REPOSITORIO](https://github.com/matiasoviedo28/RadioLocal-VHF-HF)

---

### 🧠 De dónde vengo

Antes de dedicarme de lleno al desarrollo trabajé en el mundo **ISP / redes informáticas**: FTTH, VoIP, soporte técnico en entornos reales y organización/liderazgo de sector. Esa etapa me dejó una base fuerte en comunicaciones, infraestructura y resolución de problemas bajo presión, cosas que hoy aplico todos los días en backend.

---

### 🔧 Además del código

Me gusta meter mano fuera de la pantalla: electrónica, equipos de radio 📻, radioafición, servidores y una **granja de impresoras Bambu Lab corriendo 24/7**. Esa mezcla de hardware + software + redes es la que me hace disfrutar resolver problemas de verdad.

---

### 📫 Contacto

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white) matiasalbertooviedogonzalez@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matias-alberto-oviedo-gonzalez/)

📍 Merlo, San Luis, Argentina