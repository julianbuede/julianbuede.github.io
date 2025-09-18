---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # ---------- NUEVO: Boletín + Formulario embebido (dos columnas) ----------
  - block: cta-card
    id: boletin-embed
    content:
      title: ""
      text: |
        <div class="container mx-auto">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
            <!-- Columna izquierda: título + bajada -->
            <div>
              <h2 class="text-3xl font-bold mb-3">Boletín MetaDocencia</h2>
              <p class="text-lg leading-relaxed mb-4">
                Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés.
              </p>
              <p class="mb-0">
                <a href="https://www.metadocencia.org/boletines/" class="underline font-semibold" target="_blank" rel="noopener">Ver ediciones anteriores</a>
              </p>
            </div>

            <!-- Columna derecha: formulario Mailchimp (versión responsiva sin CSS/JS externos) -->
            <div>
              <style>
                /* Contenedor y tipografía del form */
                #mc_embed_signup {
                  background: #fff;
                  font-size: 16px;
                  line-height: 1.4;
                }
                #mc_embed_signup form {
                  display: block;
                  width: 100%;
                }
                #mc_embed_signup .mc-field-group {
                  margin-bottom: 0.75rem;
                }
                #mc_embed_signup label {
                  display: block;
                  margin-bottom: 0.25rem;
                  font-weight: 600;
                }
                #mc_embed_signup input[type="email"],
                #mc_embed_signup input[type="text"] {
                  width: 100%;
                  padding: 0.6rem 0.75rem;
                  border: 1px solid #d1d5db; /* gray-300 */
                  border-radius: 0.5rem;
                  outline: none;
                }
                #mc_embed_signup input[type="email"]:focus,
                #mc_embed_signup input[type="text"]:focus {
                  border-color: #9ca3af;     /* gray-400 */
                  box-shadow: 0 0 0 3px rgba(59,130,246,.15); /* focus ring suave */
                }
                #mc_embed_signup .asterisk { color: #ef4444; }   /* rojo */
                #mc_embed_signup .helper_text { font-size: 0.8rem; color:#6b7280; }
                #mc_embed_signup .button {
                  display: inline-block;
                  background: #C83737;      /* rojo formación */
                  color: #fff;
                  border: 0;
                  border-radius: 0.5rem;
                  padding: 0.6rem 1rem;
                  font-weight: 700;
                  cursor: pointer;
                }
                #mc_embed_signup .button:hover { filter: brightness(0.95); }
                #mc_embed_signup .indicates-required {
                  font-size: 0.85rem;
                  color: #6b7280;
                  margin-bottom: 0.5rem;
                }
              </style>

              <div id="mc_embed_shell">
                <div id="mc_embed_signup">
                  <form action="https://metadocencia.us19.list-manage.com/subscribe/post?u=92fb89ce82f9689a3b083bb35&amp;id=d8187ceaf7&amp;f_id=00f682e4f0"
                        method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" target="_blank" novalidate>
                    <div id="mc_embed_signup_scroll">
                      <div class="indicates-required"><span class="asterisk">*</span> campo obligatorio</div>

                      <div class="mc-field-group">
                        <label for="mce-EMAIL">Correo electrónico <span class="asterisk">*</span></label>
                        <input type="email" name="EMAIL" class="required email" id="mce-EMAIL" required value="">
                        <span id="mce-EMAIL-HELPERTEXT" class="helper_text">E-mail</span>
                      </div>

                      <div class="mc-field-group">
                        <label for="mce-FNAME">Nombre</label>
                        <input type="text" name="FNAME" id="mce-FNAME" value="">
                      </div>

                      <div class="mc-field-group">
                        <label for="mce-LNAME">Apellido</label>
                        <input type="text" name="LNAME" id="mce-LNAME" value="">
                      </div>

                      <!-- Campos opcionales (podés dejarlos o quitarlos) -->
                      <div class="mc-field-group">
                        <label for="mce-MMERGE7">País</label>
                        <input type="text" name="MMERGE7" id="mce-MMERGE7" value="">
                      </div>
                      <div class="mc-field-group">
                        <label for="mce-MMERGE9">Comunidad</label>
                        <input type="text" name="MMERGE9" id="mce-MMERGE9" value="">
                      </div>

                      <!-- Tags ocultos (se conservan) -->
                      <div hidden>
                        <input type="hidden" name="tags" value="6238401,6541797,6397245">
                      </div>

                      <!-- Honeypot anti-bots (no tocar) -->
                      <div aria-hidden="true" style="position:absolute; left:-5000px;">
                        <input type="text" name="b_92fb89ce82f9689a3b083bb35_d8187ceaf7" tabindex="-1" value="">
                      </div>

                      <div class="optionalParent">
                        <div class="clear foot" style="margin-top:0.5rem;">
                          <input type="submit" name="subscribe" id="mc-embedded-subscribe" class="button" value="Suscribirme">
                        </div>
                      </div>
                    </div>
                  </form>
                </div>
              </div>

            </div>
          </div>
        </div>
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#FFFFFF;color:#111827;"

  # ---------- Intro compacta ----------
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "Súmate y apoya a nuestra comunidad"
          text: "Suscríbete al boletín, únete a Slack, conecta con comunidades amigas y apoya a MetaDocencia. Potenciemos a América Latina en el mapa de la investigación global."
          image: "quienessomos.jpg"
    design:
      css_class: "text-gray-900 dark:text-gray-100"
      css_style: "background-color:#F9FAFB;"

  # ---------- Boletín (ROJO) — OPCIONAL: eliminá esta sección si no querés duplicar ----------
  - block: cta-card
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: "Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés. **[Ver ediciones anteriores](https://www.metadocencia.org/boletines/)**"
      button:
        text: "Suscribite acá: Formulario de suscripción"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "text-gray-900 dark:text-gray-100"
        css_style: "background-color:#C83737"

  # ---------- Slack (ROSA) ----------
  - block: cta-card
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: |
        Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración.
        <a href="https://zenodo.org/records/10028136" style="color:#1F2937;text-decoration:underline;">Qué es Slack y cómo puedo sumarme a la conversación</a>
      button:
        text: "Unirme al espacio de Slack de MetaDocencia"
        url: "https://w3id.org/metadocencia/slack"
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#E01E5A;color:#FFFFFF;"

  # ---------- Comunidades amigas (NARANJA) ----------
  - block: cta-card
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: |
        Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario.

        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 items-center mt-4">
          <img src="/media/logos/comunidades/logo01.png" alt="Comunidad 1" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo02.png" alt="Comunidad 2" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo03.png" alt="Comunidad 3" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo04.png" alt="Comunidad 4" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo05.png" alt="Comunidad 5" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo06.png" alt="Comunidad 6" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo07.png" alt="Comunidad 7" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo08.png" alt="Comunidad 8" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo09.png" alt="Comunidad 9" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo10.png" alt="Comunidad 10" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo11.png" alt="Comunidad 11" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo12.png" alt="Comunidad 12" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo13.png" alt="Comunidad 13" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo14.png" alt="Comunidad 14" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo15.png" alt="Comunidad 15" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo16.png" alt="Comunidad 16" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo17.png" alt="Comunidad 17" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo18.png" alt="Comunidad 18" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo19.png" alt="Comunidad 19" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/comunidades/logo20.png" alt="Comunidad 20" class="max-h-10 w-auto opacity-95">
        </div>
      button:
        text: "Sumá tu comunidad"
        url: "mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad"
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#F77B20;color:#FFFFFF;"

  # ---------- Auspiciantes (AZUL) ----------
  - block: cta-card
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: |
        Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión.

        <div class="grid grid-cols-2 sm:grid-cols-3 gap-6 items-center mt-4">
          <img src="/media/logos/auspiciantes/logo01.png" alt="Auspiciante 1" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/auspiciantes/logo02.png" alt="Auspiciante 2" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/auspiciantes/logo03.png" alt="Auspiciante 3" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/auspiciantes/logo04.png" alt="Auspiciante 4" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/auspiciantes/logo05.png" alt="Auspiciante 5" class="max-h-10 w-auto opacity-95">
          <img src="/media/logos/auspiciantes/logo06.png" alt="Auspiciante 6" class="max-h-10 w-auto opacity-95">
        </div>
      button:
        text: "Acompañanos"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#00506F;color:#FFFFFF;"

  # ---------- Doná (solo botón) ----------
  - block: cta-card
    id: dona
    content:
      title: ""
      text: ""
      button:
        text: "Doná — Formulario de donación"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "border-0 shadow-none p-0"
        css_style: "background-color:transparent;color:#111827;"

  # ---------- Redes ----------
  - block: features
    id: redes
    content:
      title: "Seguí la conversación"
      text: "@metadocencia · Sumate al intercambio en redes sociales."
      items:
        - name: "X (Twitter) →"
          link: "https://twitter.com/metadocencia"
        - name: "LinkedIn →"
          link: "https://www.linkedin.com/company/metadocencia/"
        - name: "YouTube →"
          link: "https://www.youtube.com/@metadocencia"
        - name: "Instagram →"
          link: "https://www.instagram.com/metadocencia/"
        - name: "Mastodon →"
          link: "https://mastodon.social/@metadocencia"
    design:
      columns: 5
      css_class: "text-gray-900 dark:text-gray-100"
---
