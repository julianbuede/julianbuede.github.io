---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # ------------------ INTRO (compacta, sin hero grande) ------------------
  - block: markdown
    id: intro
    content:
      title: "Súmate y apoya a nuestra comunidad"
      text: |
        Sumate a nuestras iniciativas y ayudanos a hacer crecer la ciencia abierta en red.
        
        <div class="mt-4 flex flex-wrap items-center justify-center gap-3">
          <a class="btn btn-primary" href="https://www.metadocencia.org/contacto/">Suscribirme al boletín</a>
          <a class="btn btn-outline" href="https://w3id.org/metadocencia/slack">Unirme al Slack</a>
        </div>
    design:
      css_class: "text-center"

  # ------------------ BOLETÍN ------------------
  - block: markdown
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: |
        Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés.

        <div class="mt-4 flex flex-wrap items-center justify-center gap-3">
          <a class="btn btn-primary" href="https://www.metadocencia.org/contacto/">Formulario de suscripción</a>
          <a class="btn btn-outline" href="https://www.metadocencia.org/boletines/">Ver ediciones anteriores</a>
        </div>
    design:
      css_class: "text-center"

  # ------------------ SLACK ------------------
  - block: markdown
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: |
        Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración.

        <div class="mt-4 flex flex-wrap items-center justify-center gap-3">
          <a class="btn btn-primary" href="https://w3id.org/metadocencia/slack">Unirme al Slack de MetaDocencia</a>
          <a class="btn btn-outline" href="https://zenodo.org/records/10028136">Cómo sumarme</a>
        </div>
    design:
      css_class: "text-center"

  # ------------------ COMUNIDADES AMIGAS ------------------
  - block: markdown
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: |
        Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario.

        <!-- Reemplazá las imágenes por los logos reales que subas a assets/media/logos/comunidades/ -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 items-center justify-items-center mt-4">
          <img src="/media/logos/comunidades/logo1.png" alt="Comunidad 1" class="h-10 w-auto">
          <img src="/media/logos/comunidades/logo2.png" alt="Comunidad 2" class="h-10 w-auto">
          <img src="/media/logos/comunidades/logo3.png" alt="Comunidad 3" class="h-10 w-auto">
          <img src="/media/logos/comunidades/logo4.png" alt="Comunidad 4" class="h-10 w-auto">
        </div>

        <div class="mt-4">
          <a class="btn btn-outline" href="mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad%20a%20MetaDocencia">Sumá tu comunidad</a>
        </div>
    design:
      css_class: "text-center"

  # ------------------ AUSPICIANTES / APOYO ------------------
  - block: markdown
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: |
        Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión.

        <!-- Reemplazá por los logos reales en assets/media/logos/auspiciantes/ -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 items-center justify-items-center mt-4">
          <img src="/media/logos/auspiciantes/logo1.png" alt="Auspiciante 1" class="h-10 w-auto">
          <img src="/media/logos/auspiciantes/logo2.png" alt="Auspiciante 2" class="h-10 w-auto">
          <img src="/media/logos/auspiciantes/logo3.png" alt="Auspiciante 3" class="h-10 w-auto">
          <img src="/media/logos/auspiciantes/logo4.png" alt="Auspiciante 4" class="h-10 w-auto">
        </div>

        <div class="mt-4">
          <a class="btn btn-outline" href="https://www.metadocencia.org/contacto/">Acompañanos</a>
        </div>
    design:
      css_class: "text-center"

  # ------------------ DONAR ------------------
  - block: cta-card
    id: dona
    content:
      title: "Doná"
      text: "Tu contribución nos ayuda a seguir ofreciendo formación gratuita, generando recursos abiertos y fortaleciendo la comunidad."
      button:
        text: "Quiero donar"
        url: "https://www.metadocencia.org/contacto/"   # reemplazá por la URL de donación si es otra
    design:
      card:
        css_class: "bg-gray-100 dark:bg-gray-900"

  # ------------------ REDES SOCIALES (solo íconos pequeños) ------------------
  - block: markdown
    id: redes
    content:
      title: "Seguí la conversación"
      text: |
        <div class="mt-2 flex items-center justify-center gap-4">
          <!-- Subí tus íconos a assets/media/social/ y apuntá a /media/social/... -->
          <a href="https://twitter.com/metadocencia" aria-label="X (Twitter)"><img src="/media/social/x.svg" alt="X" class="h-6 w-6"></a>
          <a href="https://www.linkedin.com/company/metadocencia/" aria-label="LinkedIn"><img src="/media/social/linkedin.svg" alt="LinkedIn" class="h-6 w-6"></a>
          <a href="https://www.youtube.com/@metadocencia" aria-label="YouTube"><img src="/media/social/youtube.svg" alt="YouTube" class="h-6 w-6"></a>
          <a href="https://www.instagram.com/metadocencia/" aria-label="Instagram"><img src="/media/social/instagram.svg" alt="Instagram" class="h-6 w-6"></a>
          <a href="https://github.com/metadocencia" aria-label="GitHub"><img src="/media/social/github.svg" alt="GitHub" class="h-6 w-6"></a>
        </div>
    design:
      css_class: "text-center"
---
