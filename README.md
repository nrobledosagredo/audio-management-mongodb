# Gestión de Archivos de Audio en MongoDB

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Sistema para gestionar archivos de audio en formato `.wav` utilizando **MongoDB**. Permite almacenar, actualizar y consultar metadatos asociados a los archivos de audio, tales como fecha de grabación, ubicación, duración y tipo de fuente. Los usuarios pueden también acceder a segmentos de audio etiquetados para su posterior análisis.

## Funcionalidades

- **Gestión de base de datos MongoDB** para almacenar y organizar archivos de audio.
- **Actualización de URLs** de archivos `.wav` en la base de datos.
- **Consulta de grabaciones** por fecha de grabación y extracción de datos geoespaciales (latitud/longitud).
- **Inserción de documentos** con información detallada sobre archivos de audio y segmentos.

## Archivos

1. **crear-db**  
   Crea la base de datos y la colección `archivos`, e inserta documentos con información sobre archivos de audio y sus segmentos.

2. **agregar-audio**  
   Actualiza las URLs de los archivos de audio en la colección `archivos` en la base de datos.

3. **visualizar-consultas**  
   Realiza consultas para obtener grabaciones de una fecha específica y visualiza coordenadas geográficas (latitud/longitud).