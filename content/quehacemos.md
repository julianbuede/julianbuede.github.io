---
title: "Qué hacemos"
type: landing
slug: "que-hacemos"
design:
  spacing: "3rem"

sections:
  # ---------- HERO angosto (imagen de fondo + texto grande) ----------
  - block: hero
    content:
      title: '<span class="block text-3xl md:text-5xl font-extrabold tracking-tight text-white drop-shadow">Potenciamos el ecosistema científico latinoamericano con infraestructura, formación y comunidad.</span>'
    design:
      spacing:
        padding: ["0.75rem", 0, "0.75rem", 0]
        margin: [0, 0, 0, 0]
      css_class: ""
      css_style: "min-height: 20vh;"
      background:
        image:
          filename: "1naranjaazul.png"
          filters:
            brightness: 0.45
          size: cover
          position: center
          parallax: false
        text_color_light: true

  # ---------- Tres columnas con colores por pilar + CTA "Ver más" ----------
  - block: features
    id: pilares
    content:
      title: ""
      text: ""
      items:
        - name: "Impulsamos Infraestructura"
          icon: "cloud"
          icon_pack: "hero"
          description: |
            <div style="height:4px;background:#00506F;border-radius:6px;margin:0 0 0.75rem 0;"></div>
            Promovemos infraestructura científica y tecnológica que soporta la producción, gestión y reutilización de conocimiento.
            <br>
            <a href="#infra"
               class="mt-3 inline-block no-underline font-semibold"
               style="background:#00506F;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;">
               Ver más
            </a>

        - name: "Formamos capacidades"
          icon: "academic-cap"
          icon_pack: "hero"
          description: |
            <div style="height:4px;background:#C83737;border-radius:6px;margin:0 0 0.75rem 0;"></div>
            Creamos programas de aprendizaje colaborativo y basados en evidencia, que convierten conocimientos en acción, impulsando una investigación más abierta, eficiente y sostenible.
            <br>
            <a href="#formacion"
               class="mt-3 inline-block no-underline font-semibold"
               style="background:#C83737;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;">
               Ver más
            </a>

        - name: "Construimos comunidad"
          icon: "user-group"
          icon_pack: "hero"
          description: |
            <div style="height:4px;background:#F77B20;border-radius:6px;margin:0 0 0.75rem 0;"></div>
            Fomentamos redes de apoyo y colaboración que trascienden disciplinas, instituciones y países, para crecer y potenciar la ciencia desde América Latina hacia el mundo.
            <br>
            <a href="#comunidad"
               class="mt-3 inline-block no-underline font-semibold"
               style="background:#F77B20;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;">
               Ver más
            </a>
    design:
      columns: 3
      css_class: "text-gray-900 dark:text-gray-100"

  # ---------- PROYECTOS DESTACADOS ----------
  - block: features
    id: destacados
    content:
      title: "Proyectos destacados"
      text: ""
      items:
        - name: "Formación en Ciencia Abierta"
          description: |
            Bajada.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a><br>

            <a href="#formacion"
               class="mt-3 inline-block no-underline font-semibold"
               style="background-color:#C83737;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;display:inline-block;">
               Conoce más proyectos de formación
            </a>

        - name: "Contextualización"
          description: |
            Desarrollamos recursos de calidad en español a partir de material originalmente publicado en otro idioma.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a><br>

            <a href="#infra"
               class="mt-3 inline-block no-underline font-semibold"
               style="background-color:#00506F;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;display:inline-block;">
               Conoce más proyectos de infraestructura
            </a>

        - name: "Gobernanza"
          description: |
            Brindamos herramientas y asesoramiento en gobernanza para que personas y organizaciones logren mayor impacto y eficiencia.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a><br>

            <a href="#comunidad"
               class="mt-3 inline-block no-underline font-semibold"
               style="background-color:#F77B20;color:#FFFFFF;padding:0.5rem 0.9rem;border-radius:0.5rem;display:inline-block;">
               Conoce más proyectos de comunidad
            </a>
    design:
      columns: 3
      css_class: "text-gray-900 dark:text-gray-100"

  # ======================
  #  SECCIÓN: INFRAESTRUCTURA (AZUL)
  # ======================
  - block: cta-card
    id: infra
    content:
      title: "Impulsamos Infraestructura"
      text: "Promovemos infraestructura abierta, sostenible y orientada al reuso, para acelerar la producción y circulación del conocimiento."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#00506F;color:#FFFFFF;"

  - block: features
    id: infra-proyectos
    content:
      title: "Proyectos de Infraestructura"
      text: ""
      items:
        - name: "Catalyst"
          description: |
            Mejoramos la accesibilidad y la utilidad de la infraestructura en la nube para comunidades globales.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Contextualización"
          description: |
            Desarrollamos recursos de calidad en español a partir de material originalmente publicado en otro idioma.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Ciencia Abierta y Datos Abiertos en la comunidad latinoamericana de bioimagen"
          description: |
            Proyecto a incubar

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
    design:
      columns: 3

  - block: stats
    content:
      items:
        - statistic: "X"
          description: "proyectos financiados"
        - statistic: "+200"
          description: "documentos en Zenodo"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Testimonio 1"
          role: "Organización/Proyecto"
          text: "Testimonio 1"
        - name: "Testimonio 2"
          role: "Organización/Proyecto"
          text: "Testimonio 2."
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # ======================
  #  SECCIÓN: FORMACIÓN (ROJO)
  # ======================
  - block: cta-card
    id: formacion
    content:
      title: "Formamos capacidades"
      text: "Diseñamos experiencias de aprendizaje basadas en evidencia, centradas en la práctica y con foco en el impacto."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#C83737;color:#FFFFFF;"

  - block: features
    id: formacion-proyectos
    content:
      title: "Proyectos de Formación"
      text: ""
      items:
        - name: "Formación en Ciencia Abierta"
          description: |
            Diseñamos formación en Ciencia Abierta en español, contextualizada a América Latina, para llevar buenas prácticas a la acción.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Financiamiento"
          description: |
            Formación que impulsa la financiación internacional para América Latina.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Formación para Formar"
          description: |
            Atendemos la demanda de habilidades pedagógicas prácticas en comunidades hispanohablantes dedicadas a la ciencia y la tecnología.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
    design:
      columns: 3

  - block: stats
    content:
      items:
        - statistic: "94"
          description: "ediciones (388 horas)"
        - statistic: "+1500"
          description: "personas de 33 países formadas"
        - statistic: "89%"
          description: "Net Promoter Score"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Walter Sosa Escudero"
          role: ""
          text: "No se pierdan esto. Es gente hiperprofesional, es buenísimo el trabajo que hacen."
        - name: "Emmanuel Iarussi"
          role: ""
          text: "El curso fue excelente. Me devolvieron el impulso de enseñar. Enseñar en línea puede ser mucho más humano de lo que podría haber imaginado."
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # ======================
  #  SECCIÓN: COMUNIDAD (NARANJA)
  # ======================
  - block: cta-card
    id: comunidad
    content:
      title: "Construimos comunidad"
      text: "Facilitamos redes de colaboración que conectan disciplinas, instituciones y países, desde y para América Latina."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#F77B20;color:#FFFFFF;"

  - block: features
    id: comunidad-proyectos
    content:
      title: "Proyectos de Comunidad"
      text: ""
      items:
        - name: "Gobernanza"
          description: |
            Brindamos herramientas y asesoramiento en gobernanza para que personas y organizaciones logren mayor impacto y eficiencia.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Conversatorios"
          description: |
            Organizamos conversatorios y espacios de diálogo para explorar, aprender y compartir conocimiento. Fomentamos la participación y el intercambio de experiencias para fortalecer redes de colaboración y el conocimiento compartido.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
        - name: "Mapeo de Ciencia Abierta en Latinoamérica"
          description: |
            Repositorio colaborativo de información sobre Ciencia Abierta en español. Proyecto a incubar.

            <a class="mt-2 inline-block font-semibold underline underline-offset-4" href="https://julianbuede.github.io/blog/second-brain/">Ver más →</a>
    design:
      columns: 3

  - block: stats
    content:
      items:
        - statistic: "+40"
          description: "comunidades amigas"
        - statistic: "54"
          description: "personas colaboradoras"
        - statistic: "+1000"
          description: "personas en Slack"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Andrés Kamaid"
          role: "Researcher, Institut Pasteur Montevideo — tras consultoría para Latin American Bioimaging"
          text: "I want to thank you for the work done so far. In addition to your conceptual and practical contributions, which have enabled us to make significant progress, your warmth and kindness have made this process truly enjoyable. I will miss our meetings."
        - name: "Verónica Xhardez"
          role: "ARPHAI"
          text: "¡Cuánto aprendizaje colectivo por el camino! 🍎 Felicitaciones y gracias por ser un ámbito de coproducción, interdisciplina y cuidado mutuo."
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
---
