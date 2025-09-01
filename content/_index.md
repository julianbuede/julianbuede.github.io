---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Potenciemos a América Latina en el mapa de la investigación global
      primary_action:
        text: Súmate
        url: https://hugoblox.com/templates/](https://www.metadocencia.org/suscripcion/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: 1naranjaazul.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Somos
          text: Construimos capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo
          # Upload image to `assets/media/` and reference the filename here
          image: prueba-home2.jpg
          button:
            text: Conócenos
            url: https://hugoblox.com/templates/
        - title: Qué hacemos
          text: Trabajamos para que la producción, la comunicación y la aplicación de saberes científicos y técnicos sean globalmente equitativos.
          # Upload image to `assets/media/` and reference the filename here
          image: organigramaMD2025-04.png
          button:
            text: Conoce nuestros proyectos
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"  
  - block: features
    id: features
    content:
      title: Nuestros pilares
      text: Build your site with blocks 🧱
      items:
        - name: Impulsamos infraestructura
          icon: rectangle-group
          description: Proyectos
        - name: Formamos a personas investigadoras
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Construimos comunidad
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  - block: stats
    content:
      items:
        - statistic: "NN"
          description: |
            Proyectos  
            financiados
        - statistic: "+1500"
          description: |
            personas  
            formadas
        - statistic: "+1000"
          description: |
            personas en la   
            comunidad de Slack
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
