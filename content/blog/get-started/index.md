---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"         # puedes cambiarlo a lo que prefieras (ruta /cta/)
design:
  spacing: "3rem"

sections:
  # ------------------ HERO ------------------
  - block: hero
    content:
      title: "Súmate y apoya a nuestra comunidad"
      text: "Recibí nuestras novedades, unite al Slack, sumá tu comunidad, apoyá y ayudanos a hacer crecer la ciencia abierta en red."
      primary_action:
        text: "Suscribirme al boletín"
        url: "https://www.metadocencia.org/contacto/"
      secondary_action:
        text: "Unirme al Slack"
        url: "https://w3id.org/metadocencia/slack"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: "quienessomos.jpg"
          filters: { brightness: 0.35 }
        text_color_light: true

  # ------------------ BOLETÍN ------------------
  - block: markdown
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: |
        Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés.

        - 👉 **[Formulario de suscripción](https://www.metadocencia.org/contacto/){.btn .btn-primary}**
        - 📚 **[Ver ediciones anteriores](https://www.metadocencia.org/boletines/){.btn .btn-outline}**

  # ------------------ SLACK ------------------
  - block: cta-card
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: "Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración."
      button:
        text: "Unirme al Slack de MetaDocencia"
        url: "https://w3id.org/metadocencia/slack"
    design:
      card:
        css_class: "bg-primary-700 text-white"

  # ------------------ COMUNIDADES AMIGAS ------------------
  - block: markdown
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: |
        Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario.

        <!-- Reemplazá las imágenes por los logos reales que subas a assets/media/logos/comunidades/ -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 items-center">
          <img src="/media/logos/comunidades/logo1.png" alt="Comunidad 1">
          <img src="/media/logos/comunidades/logo2.png" alt="Comunidad 2">
          <img src="/media/logos/comunidades/logo3.png" alt="Comunidad 3">
          <img src="/media/logos/comunidades/logo4.png" alt="Comunidad 4">
        </div>

        <div class="mt-4">
          <a class="btn btn-outline" href="https://www.metadocencia.org/contacto/">Sumá tu comunidad</a>
        </div>

  # ------------------ AUSPICIANTES / APOYO ------------------
  - block: markdown
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: |
        Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión.

        <!-- Reemplazá por los logos reales en assets/media/logos/auspiciantes/ -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 items-center">
          <img src="/media/logos/auspiciantes/logo1.png" alt="Auspiciante 1">
          <img src="/media/logos/auspiciantes/logo2.png" alt="Auspiciante 2">
          <img src="/media/logos/auspiciantes/logo3.png" alt="Auspiciante 3">
          <img src="/media/logos/auspiciantes/logo4.png" alt="Auspiciante 4">
        </div>

        <div class="mt-4">
          <a class="btn btn-outline" href="https://www.metadocencia.org/contacto/">Acompañanos</a>
        </div>

  # ------------------ DONAR ------------------
  - block: cta-card
    id: dona
    content:
      title: "Doná"
      text: "Tu contribución nos ayuda a seguir ofreciendo formación gratuita, generando recursos abiertos y fortaleciendo la comunidad."
      button:
        text: "Quiero donar"
        url: "https://www.metadocencia.org/contacto/"   # reemplazá por el formulario de donación si tenés otra URL
    design:
      card:
        css_class: "bg-gray-100 dark:bg-gray-900"

  # ------------------ REDES SOCIALES ------------------
  - block: features
    id: redes
    content:
      title: "Seguí la conversación"
      text: "Sumate al intercambio en redes sociales."
      items:
        - name: "@metadocencia en X (Twitter)"
          icon: twitter
          icon_pack: fab
          description: "Novedades y conversaciones."
          link: "https://twitter.com/metadocencia"
        - name: "LinkedIn"
          icon: linkedin
          icon_pack: fab
          description: "Comunidad y oportunidades."
          link: "https://www.linkedin.com/company/metadocencia/"
        - name: "YouTube"
          icon: youtube
          icon_pack: fab
          description: "Charlas y recursos."
          link: "https://www.youtube.com/@metadocencia"
        - name: "Instagram"
          icon: instagram
          icon_pack: fab
          description: "Historias y comunidad."
          link: "https://www.instagram.com/metadocencia/"
    design:
      columns: 4
---
