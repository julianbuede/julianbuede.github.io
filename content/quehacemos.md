---
title: "Qué hacemos"
type: landing
slug: "que-hacemos"
design:
  spacing: "3rem"

sections:
  # Intro (imagen + texto)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Qué hacemos"
          text: "Potenciamos el ecosistema científico latinoamericano con infraestructura, formación y comunidad."
          image: "organigramaapaisado.png"  # asegurate de tenerla en assets/media/
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  # Tres columnas en recuadros (cards) con CTA
  - block: markdown
    id: pilares
    content:
      title: ""
      text: |
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <!-- Card 1 -->
          <div class="rounded-2xl border border-gray-200/70 dark:border-gray-700/70 bg-white dark:bg-gray-900 p-6 shadow-sm hover:shadow transition">
            <h3 class="text-xl font-semibold mb-2">Impulsamos Infraestructura</h3>
            <p class="text-gray-700 dark:text-gray-300">
              Promovemos infraestructura científica y tecnológica que soporta la producción, gestión y reutilización de conocimiento.
            </p>
            <a href="/que-hacemos/infraestructura/" class="btn btn-primary mt-4 inline-block">Ver más</a>
          </div>

          <!-- Card 2 -->
          <div class="rounded-2xl border border-gray-200/70 dark:border-gray-700/70 bg-white dark:bg-gray-900 p-6 shadow-sm hover:shadow transition">
            <h3 class="text-xl font-semibold mb-2">Formamos capacidades</h3>
            <p class="text-gray-700 dark:text-gray-300">
              Creamos programas de aprendizaje colaborativo y basados en evidencia, que convierten conocimientos en acción, impulsando una investigación más abierta, eficiente y sostenible.
            </p>
            <a href="/que-hacemos/formacion/" class="btn btn-primary mt-4 inline-block">Ver más</a>
          </div>

          <!-- Card 3 -->
          <div class="rounded-2xl border border-gray-200/70 dark:border-gray-700/70 bg-white dark:bg-gray-900 p-6 shadow-sm hover:shadow transition">
            <h3 class="text-xl font-semibold mb-2">Construimos comunidad</h3>
            <p class="text-gray-700 dark:text-gray-300">
              Fomentamos redes de apoyo y colaboración que trascienden disciplinas, instituciones y países, para crecer y potenciar la ciencia desde América Latina hacia el mundo.
            </p>
            <a href="/que-hacemos/comunidad/" class="btn btn-primary mt-4 inline-block">Ver más</a>
          </div>
        </div>
    design:
      css_class: "text-gray-900 dark:text-gray-100"
---
