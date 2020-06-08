---
title: ""
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.15"
  overlay_image: /assets/images/index/hero.jpg
  actions:
    - label: "Cotizar"
      url: "quote.html"
  caption: ""
excerpt: "Protege tu futuro. Protege tu patrimonio. Protege a tu familia."
intro: 
  - excerpt: 'En asegura + trabajamos para proteger lo que mas quieres.'
feature_row:
  - image_path: assets/images/types/segurocoche.jpg
    alt: "coche"
    title: "Seguros de Automovil"
    excerpt: "Los seguros de automovil te ayudan a manejar protegido."
    url: "auto.html"
    btn_label: "Ver mas"
    btn_class: "btn--primary"
  - image_path: /assets/images/types/seguromedico.jpg
    alt: "medico"
    title: "Seguros de Gastos Medicos"
    excerpt: "La mejor manera de proteger tu salud."
    url: "medical.html"
    btn_label: "Ver mas"
    btn_class: "btn--primary"
  - image_path: /assets/images/types/segurovida.jpg
    title: "Seguros de Vida"
    excerpt: "Para que tu familia salga adelante."
    url: "life.html"
    btn_label: "Ver mas"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}