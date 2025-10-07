# Relevamiento diario del Boletín Oficial de la Ciudad de Buenos Aires

Este repositorio contiene un script desarrollado en Python (Google Colab) para automatizar la búsqueda diaria de normativa vinculada al ejercicio profesional de la arquitectura en los ejemplares del Boletín Oficial de la Ciudad Autónoma de Buenos Aires.
Trabaja por keywords + patrones de pertinencia en ventanas de contexto ±300 palabras y exporta un Excel con dos hojas.

## Objetivo

Facilitar la detección de disposiciones, resoluciones, leyes, decretos y otra normativa urbanística o edilicia mediante la búsqueda automatizada de términos clave y expresiones regulares en el PDF diario del Boletín.

## Características

- Entrada: PDF(s) del Boletín Oficial (subidos manualmente).
- Búsqueda: detección de keywords y evaluación de patrones de pertinencia (verbos normativos) dentro del contexto del keyword.
- Salida: Excel con dos hojas:
    1. Pertinentes (keywords+patrones) — contextos donde coexisten keyword(s) y patrón(es).
    2. Todos los hallazgos — todos los contextos donde hubo keyword(s), con o sin patrón.

## Instrucciones de uso

1. Abrí Analisis_BO_CABA_sin_LLM.ipynb en Colab.
2. Ejecutá las celdas de instalación e importaciones.
3. Subí uno o más PDF del Boletín Oficial (celda de subida).
4. Ejecutá la celda de procesamiento.
5. Descargá el Excel generado: Resultados_BO_CABA_sin_LLM_YYYYMMDD_HHMM.xlsx.

## Licencia

Este proyecto está disponible bajo la [Licencia MIT](LICENSE).  
Se permite su uso, copia, modificación y redistribución con o sin fines comerciales, siempre que se mantenga la atribución correspondiente.


## Autor:
Juan Draghi — Biblioteca del Consejo Profesional de Arquitectura y Urbanismo (con la asistencia de ChatGPT)
