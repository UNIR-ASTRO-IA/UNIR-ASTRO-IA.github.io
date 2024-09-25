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
  - excerpt: 'Este proyecto está formado por un grupo interdisciplinar de astrónomos y
científicos de datos que pretenden aunar esfuerzos entre ambas comunidades para obtener
el máximo rendimiento posible de los datos astronómicos aportando soluciones de DL
específicas a problemas determinados. En particular, y de cara a concretar objetivos
científicos determinados que suponen un punto de encuentro y de interés común entre todos
los miembros del equipo, esta propuesta se centra en los siguientes aspectos.
En primer lugar, en el análisis y clasificación de curvas de luz en las que se haya identificado
la presencia de un tránsito periódico, de cara a determinar la naturaleza astrofísica de dicho
tránsito, es decir, si ha sido producido por un exoplaneta, por una compañera binaria, etc.
Esta operación es conocida en la ciencia de exoplanetas como vetting.
En segundo lugar, se abordan dos problemas que se pueden considerar relacionados por el
tipo de técnicas de Deep Learning que se aplicarán. Se trata en primer lugar de la tarea de
deconvolución ciega, en la que se pretende mejorar una imagen mediante la eliminación de
la interferencia producida por efectos como la interposición de la atmósfera, y en cierta
medida las características propias del instrumento, especialmente en los casos donde no es
posible eliminarlas mediante una calibración de tipo clásico. Esto incluye efectos debidos a
la degradación del instrumental con el tiempo. En segundo lugar, la posibilidad de
incrementar la resolución (superresolución) utilizando para ello información redundante en la
imagen, o información procedente de varias imágenes.'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}