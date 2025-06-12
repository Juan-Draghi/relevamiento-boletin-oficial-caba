# Relevamiento diario del Boletín Oficial de la Ciudad de Buenos Aires

Este repositorio contiene un script desarrollado en Python (Google Colab) para automatizar la búsqueda diaria de normativa vinculada al ejercicio profesional de la arquitectura en los ejemplares del Boletín Oficial de la Ciudad Autónoma de Buenos Aires.

## Objetivo

Facilitar la detección de disposiciones, resoluciones, leyes, decretos y otra normativa urbanística o edilicia mediante la búsqueda automatizada de términos clave y expresiones regulares en el PDF diario del Boletín.

## Características

- Lectura de texto desde archivos PDF del Boletín Oficial.
- Búsqueda de términos exactos y expresiones regulares.
- Posibilidad de definir palabras clave desde una lista.
- Exportación de resultados a un archivo `.xlsx` con los términos encontrados y su contexto.
- Interfaz ejecutable desde Google Colab, sin necesidad de instalación local.

## Instrucciones de uso

1. Cargar el archivo del Boletín Oficial en la carpeta predeterminada.
2. Ejecutar las celdas del notebook.
3. Descargar el archivo de resultados (`resultados_busqueda_BOCABA.xlsx`).
4. Para actualizar los términos de búsqueda, modificar la lista keywords.

## Licencia

Este proyecto está disponible bajo la [Licencia MIT](LICENSE).  
Se permite su uso, copia, modificación y redistribución con o sin fines comerciales, siempre que se mantenga la atribución correspondiente.


## Autor:
Juan Draghi — Biblioteca del Consejo Profesional de Arquitectura y Urbanismo (con la asistencia de ChatGPT)
