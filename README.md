# covidpredic.github.io
Predicciones Covid19
name: "Predicciones Covid19"
ouput_dir: "."
navbar:
  title: "COVID19"
  left:
    - text: "Motivación"
      href: index.html

    - text: "Predicciones"
      menu:
        - text: "Metodología"
          href: about.html
        - text: "Análisis gráfico"
          href: Page-a.html
        - text: "Tabla de predicciones"
          href: Page-b.html
      href: about.html
output:
  html_document:
    theme: cosmo
    highlight: textmate
    css: styles.css
    font-family: Helvetica
    font-size: 16pt
