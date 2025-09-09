---
title: "Home"
type: landing

design:
  spacing: "6rem"
  
sections:
  - block: hero
    content:
      title: Quiénes somos
      text: MetaDocencia es una organización sin fines de lucro fundada en 2020. Nuestra comunidad construye capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo.
    primary_action:
        text: Nuestra Gobernanza
        url: https://hugoblox.com/templates/](https://www.metadocencia.org/suscripcion/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: quienessomos.jpg
          filters:
            brightness: 0.3
        text_color_light: true
    
  - block: markdown
    +++
# A "Meet the Team" section created with the People widget.
# This section displays people from `content/authors/` which belong to the `user_groups` below.

widget = "people"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1 # Order that this section will appear.

title = "Comunidades amigas"
subtitle = "Siempre felices de agrandar el panal. Para más información, escríbenos a [comunidad@metadocencia.org](mailto:comunidad@metadocencia.org)."

[content]
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups = ["Comunidades amigas"]

[design]
  # Show user's social networking links? (true/false)
  show_social = true

  # Show user's interests? (true/false)
  show_interests = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
    
 - block: cta-image-paragraph
    content:
      items:
        -
          name: "First Item"
          description: "Description for first item"
        -
          name: "Second Item"
          description: "Description for second item"
    design:
      background:
        color: ""
        # gradient_start: "#4f46e5"
        # gradient_end: "#7c3aed"
        # text_color_light: true
      # spacing:
      #   padding: ["6", "6", "6", "6"]
      # columns: "1"

  - block: resume-biography
    content:
      username: "admin"
      text: "This is sample text content for the section."
      button:
        text: "Click Here"
        url: "https://example.com"
    design:
      background:
        color: ""
        # gradient_start: "#4f46e5"
        # gradient_end: "#7c3aed"
        # text_color_light: true
      # spacing:
      #   padding: ["6", "6", "6", "6"]
      # columns: "1"

  - block: cta-button-list
    content:
      title: "Choose Your Path"
      text: "Multiple ways to get started with our platform"
      buttons:
        - text: "For Researchers"
          url: "/researchers"
          icon: "academic-cap"
        - text: "For Businesses"
          url: "/business"
          icon: "building-office"
        - text: "For Students"
          url: "/students"
          icon: "book-open"
    design:
      columns: "3"
      background:
        color: "blue-50"
    
  - block: features
    content:
      title: "Amazing Features"
      text: "Discover what makes our platform special"
      items:
        - name: "Fast Performance"
          description: "Lightning-fast load times for better user experience"
          icon: "bolt"
        - name: "Easy to Use"
          description: "Intuitive interface that anyone can master"
          icon: "heart"
        - name: "Secure"
          description: "Enterprise-grade security built-in"
          icon: "shield-check"
    design:
      columns: "3"
      background:
        color: "gray-50"
    
  - block: resume-awards
    content:
      username: "admin"
      title: "My Section Title"
      text: "This is sample text content for the section."
    design:
      background:
        color: ""
        # gradient_start: "#4f46e5"
        # gradient_end: "#7c3aed"
        # text_color_light: true
      # spacing:
      #   padding: ["6", "6", "6", "6"]
      # columns: "1"
    
  - block: resume-biography-3
    content:
      username: "admin"
      text: "This is sample text content for the section."
      button:
        text: "Click Here"
        url: "https://example.com"
    design:
      background:
        color: ""
        # gradient_start: "#4f46e5"
        # gradient_end: "#7c3aed"
        # text_color_light: true
      # spacing:
      #   padding: ["6", "6", "6", "6"]
      # columns: "1"
    
  - block: resume-experience
    content:
      title: "Experience"
      items:
        - title: "Senior Developer"
          company: "Tech Company"
          location: "San Francisco, CA"
          date_start: "2020-01-01"
          date_end: ""
          description: |
            * Led development of key features
            * Mentored junior developers
            * Improved system performance by 40%
        - title: "Software Engineer"
          company: "Startup Inc"
          location: "New York, NY"
          date_start: "2018-06-01"
          date_end: "2019-12-31"
          description: "Developed web applications using modern technologies"
    design:
      columns: "1"
    
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Vamos por 5 años más
          text: Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades. Gracias por estos primeros 5 años de aprendizaje, colaboración y crecimiento. ¡Vamos por 5 años más!
          # Upload image to `assets/media/` and reference the filename here
          image: quienesomos.jpg
          button:
            text: Conócenos
            url: https://hugoblox.com/templates/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
    
  - block: stats
    content:
      items:
        - statistic: "+1,000"
          description: |
            personas en Slack
        - statistic: "+40"
          description: |
            socios y patrocinadores
        - statistic: "88"
          description: |
            personas contribuyen a nuestro trabajo
        - statistic: "+6000"
          description: |
            personas conectadas en redes sociales
        - statistic: "+2600"
          description: |
            personas suscriptas a nuestro boletín
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, "1rem", 0, "1rem"]

  - block: markdown
    id: solutions
    content:
      title: ""
      text: |
        <div class="row g-4 align-items-center">
          <div class="col-md-6">
            <img src="/media/quienesomos.jpg" alt="Personas de MetaDocencia colaborando en un taller en línea" class="img-fluid rounded mb-3">
            <h3>Quiénes somos</h3>
            <p>MetaDocencia es una organización sin fines de lucro fundada en 2020. Nuestra comunidad construye capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo.</p>
            <a class="btn btn-primary" href="/institucional/">Conócenos</a>
          </div>
          <div class="col-md-6">
            <img src="/media/organigramaapaisado.png" alt="Organigrama y líneas de trabajo de MetaDocencia" class="img-fluid rounded mb-3">
            <h3>Qué hacemos</h3>
            <p>Trabajamos para que la producción, comunicación y aplicación de saberes científicos y técnicos sean globalmente equitativos.</p>
            <ul>
              <li>Impulsamos infraestructura</li>
              <li>Formamos a personas investigadoras</li>
              <li>Construimos comunidad</li>
            </ul>
            <a class="btn btn-outline-primary" href="/proyectos/">Conoce nuestros proyectos</a>
          </div>
        </div>
    design:
      background:
        color: "#f6f7fb"

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "3 TESTIMONIOS A DEFINIR - Julio Zetter"
          role: " Coordinador en Jefe de la base de datos y hemeroteca virtual SciELO México"
          # Upload image to `assets/media/` and reference the filename here
          image: "juliozetter.jpeg"
          text: "No cabe más que agradecer a los instructores que hicieron posible este curso, que sin duda es la semilla de grandes frutos. Gracias por tanto MetaDocencia"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
    
  - block: cta-card
    content:
      title: Apoya a la ciencia latinoamericana
      text: Aquí te contamos cómo
      button:
        text: Súmate
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
