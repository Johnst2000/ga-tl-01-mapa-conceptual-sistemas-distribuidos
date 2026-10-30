# ga-tl-01-mapa-conceptual-sistemas-distribuidos
Mapa conceptual colaborativo del ecosistema de sistemas distribuidos. Actividad GA-TL-01, Unidad 1. UTEQ.
## Mapa conceptual en Miro

El mapa conceptual colaborativo fue desarrollado utilizando la herramienta Miro.

**[Ver mapa conceptual en Miro](https://miro.com/welcomeonboard/NFNSMExHMk8xdUI3d2VpMXJ3L29lTXR2b1ZzVW0xSE9FQjJVTGp3OXUyV3l4UUhGU2pLUVNpQ1Z0dEo2L1JHR054U1RLb0plZWlJeHBsZEUxMXBCd3RJdk1ySFV0UzFIdm1DNkNrZy95OStVaGpsY2I2RHoydk5TWUNnVlA4V1JBd044SHFHaVlWYWk0d3NxeHNmeG9BPT0hdjE=?share_link_id=329689635656)**

## Documento en LaTeX

El repositorio contiene los archivos fuente del documento académico, permitiendo su visualización, edición y compilación mediante Overleaf.

**Archivos necesarios:**
- `documento.tex`: contenido principal del documento.
- `referencias.bib`: referencias bibliográficas en formato IEEE.

### Instrucciones para abrir el documento

1. Descargar los archivos de la carpeta `latex` del repositorio.
2. Ingresar a [Overleaf](https://www.overleaf.com/).
3. Crear un proyecto nuevo seleccionando **New Project → Blank Project**.
4. Subir los archivos `documento.tex` y `referencias.bib`.
5. Abrir `documento.tex` y seleccionarlo como archivo principal.
6. Seleccionar el compilador **pdfLaTeX**.
7. Presionar **Recompile** para generar el documento PDF.

### Referencias bibliográficas

El documento utiliza BibTeX con el estilo IEEE. Al final del archivo principal se encuentran las instrucciones:

```latex
\bibliographystyle{IEEEtran}
\bibliography{referencias}
```

Estas permiten incorporar automáticamente las referencias bibliográficas desde el archivo `referencias.bib`.

**Nota:** Ambos archivos deben permanecer dentro del mismo proyecto de Overleaf para que las referencias se generen correctamente.
