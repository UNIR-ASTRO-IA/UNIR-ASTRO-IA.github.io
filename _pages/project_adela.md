---
title: "Project ADELA"
layout: splash
permalink: /project_adela/
date: 2024-09-25T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Este proyecto nace con la intención de ayudar a cubrir el hueco todavía existente entre
ambas disciplinas (astrofísica y ciencia de datos) en el uso y entendimiento de las técnicas
de ML y DL en el análisis de datos astronómicos. En nuestra opinión, la llegada de nuevos
instrumentos que proporcionarán una masiva cantidad de datos astronómicos, como Large
Synoptic Survey Telescope (LSST), Euclid, James Webb Space Telescope (JWST),
PLAnetary Transits and Oscillations of stars (PLATO), etc, cuyo análisis se antoja
imprescindible con herramientas de DL, implica a su vez una imprescindible colaboración
mano a mano entre ambas comunidades."
intro: 
  - excerpt: 'Este proyecto está propulsado por un grupo interdisciplinar de astrónomos y
científicos de datos que pretenden aunar esfuerzos entre ambas comunidades para obtener
el máximo rendimiento posible de los datos astronómicos aportando soluciones de DL
específicas a problemas determinados.'

feature_row:
  - image_path: assets/images/adela/exoplanet.jpg
    alt: "Tránsito de exoplanetas"
    title: "Detección de exoplanetas"
    excerpt: "Detección de exoplanetas a partir de la detección de tránsitos, mediante el análisis automatizado de la curva de luz. "
  - image_path: /assets/images/adela/GAN_recovery.jpg
    alt: "Técnicas mejora de imagen"
    title: "Mejora de imagen mediante métodos generativos"
    excerpt: "Los modelos generativos han demostrado su utilidad en el campo de la generación de imágenes novedosas, pero también pueden ser adaptados y entrenados para resolver problemas de <em>denoising</em> y <em>super-resolution</em> en imagen astronómica."

---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

