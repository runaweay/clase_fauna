# ¿El suelo es un organismo vivo?

**Cómo las prácticas de recuperación del suelo pueden aumentar la fauna edáfica**

Clase invitada para el curso *Conservación del Suelo y Gestión del Carbono* (REN237-1), impartido por la profesora Sara Acevedo, Pontificia Universidad Católica de Chile, 10 de noviembre de 2026.

👉 **Página de la clase:** https://runaweay.github.io/clase_fauna/scripts/clase_fauna.html

## Contenido

La clase recorre 5 preguntas:

1. ¿Qué hay en el suelo?
2. ¿Qué hacen sus organismos?
3. ¿Cómo sabemos si el suelo está sano?
4. El suelo en el Antropoceno, con resultados de ensayos ecotoxicológicos con el ácaro *Oppia nitens*
5. Actividad "Detectives del suelo": extracción de mesofauna con un embudo de Berlese-Tullgren casero y observación al microscopio de dos suelos del campus San Joaquín

## Estructura del repositorio

```
clase_fauna/
├── README.md
├── scripts/
│   ├── clase_fauna.qmd      # documento Quarto (fuente)
│   └── clase_fauna.html     # página generada
├── img/                     # figuras y fotos usadas en la página
├── referencias/
│   ├── referencias.bib      # bibliografía en BibTeX
│   └── apa.csl              # estilo de citas APA 7
└── estilo/
    └── estilo.css           # estilos de la página
```

## Cómo reproducir

Requisitos: [R](https://cran.r-project.org), [Quarto](https://quarto.org) y los paquetes de R `ggplot2`, `knitr` y `rmarkdown`.

```r
install.packages(c("ggplot2", "knitr", "rmarkdown"))
```

Desde la carpeta del repositorio:

```
quarto render scripts/clase_fauna.qmd
```

El resultado es `scripts/clase_fauna.html`, un archivo único con todas las imágenes incluidas.

## Autora

Mariana dos Santos Moreno, Pontificia Universidad Católica de Chile.

Las figuras de otros autores se usan con fines educativos y se citan en la página junto a cada imagen.
