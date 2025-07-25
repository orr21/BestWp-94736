---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: "¡Únete a la revolución estudiantil de Las Palmas! \U0001F680"
      color: text-dark
      type: TitleBlock
    subtitle: Best Las Palmas - Donde los estudiantes brillan
    text: >
      Somos la asociación estudiantil más vibrante de Las Palmas. Conectamos
      estudiantes, creamos oportunidades increíbles y construimos el futuro
      juntos. ¡Tu aventura universitaria comienza aquí!
    actions:
      - label: ¡Únete ahora!
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: Descubre más
        altText: ''
        url: /sobre-nosotros
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Estudiantes de Best Las Palmas unidos
      elementId: ''
      type: ImageBlock
    badge:
      label: '¡Nuevo semestre, nuevas aventuras!'
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: "¿Por qué Best Las Palmas es increíble? \U0001F31F"
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Descubre todo lo que podemos hacer juntos
    items:
      - type: FeaturedItem
        title: 500+
        subtitle: Estudiantes activos
        text: >-
          Una comunidad vibrante de más de 500 estudiantes de todas las
          carreras. ¡Aquí encontrarás tu tribu perfecta!
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Comunidad estudiantil
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: 50+
        subtitle: Eventos al año
        text: >-
          Desde fiestas épicas hasta talleres súper útiles. Siempre hay algo
          emocionante pasando en Best Las Palmas.
        image:
          url: /images/icon2.svg
          altText: Eventos estudiantiles
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: 100%
        subtitle: Diversión garantizada
        text: >-
          Prometemos que tu experiencia universitaria será épica. Amistades para
          toda la vida, recuerdos increíbles y mucha diversión.
        image:
          url: /images/icon3.svg
          altText: Diversión estudiantil
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: ¡Quiero participar!
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: Lo mejor de ser estudiante
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Las universidades que confían en nosotros
    images:
      - url: /images/empathy-logo.svg
        altText: Universidad Las Palmas
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: ULPGC
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Universidad Fernando Pessoa
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: ESD Las Palmas
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Instituto Canarias
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Centro Universitario
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/surround-yourself-with-right-people.md
      - content/pages/blog/life-of-our-development-team.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
    title:
      text: "Historias que inspiran \U0001F4D6"
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Lee las experiencias de nuestros miembros
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: "Tu futuro comienza aquí \U0001F3AF"
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Descubre las oportunidades que te esperan
    text: |-
      En Best Las Palmas no solo estudiamos, ¡vivimos experiencias únicas!
      Desde networking con profesionales hasta eventos que marcarán tu vida
      universitaria. Aquí es donde los sueños se hacen realidad.
    media:
      title: Conoce Best Las Palmas
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: Tu nueva familia universitaria
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: GenericSection
    title:
      text: "Networking que funciona \U0001F91D"
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Conecta con profesionales y empresas top
    text: |-
      Organizamos meetups, charlas con CEOs, workshops con startups y eventos
      de networking que realmente abren puertas. Tu carrera profesional
      empieza aquí, no cuando te gradúes.
    actions:
      - label: Ver próximos eventos
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Únete al networking
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      title: Eventos de networking
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: "Eventos que no te puedes perder \U0001F389"
      color: text-dark
      type: TitleBlock
    subtitle: 'Diversión, aprendizaje y networking en uno'
    text: >
      Desde fiestas temáticas hasta hackathons, pasando por torneos de
      videojuegos y charlas inspiradoras. En Best Las Palmas siempre pasa algo
      increíble.
    actions:
      - label: Ver calendario
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Próximos eventos
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero2.svg
      altText: Eventos estudiantiles divertidos
      type: ImageBlock
    badge:
      label: Siempre hay algo nuevo
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: "Desarrollo personal y profesional \U0001F4AA"
      color: text-dark
      type: TitleBlock
    subtitle: Crece mientras te diviertes
    text: >
      Talleres de liderazgo, cursos de habilidades blandas, mentorías
      personalizadas y programas de intercambio. Invertimos en tu crecimiento
      personal y profesional.
    actions:
      - label: Explorar programas
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Solicitar mentoría
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Desarrollo estudiantil
      type: ImageBlock
    badge:
      label: Tu mejor versión te espera
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: CarouselSection
    title: null
    subtitle: "Lo que dicen nuestros miembros \U0001F4AC"
    items:
      - title: >-
          "Best Las Palmas cambió completamente mi experiencia universitaria.
          Aquí encontré mi pasión y mis mejores amigos."
        tagline: Testimonio 1
        subtitle: 'María González, Estudiante de Marketing'
        text: >-
          Llegué tímida y sin saber qué hacer con mi carrera. Ahora lidero
          proyectos, tengo una red increíble de contactos y sé exactamente hacia
          dónde voy.
        image:
          url: /images/person-placeholder-light.png
          altText: María González
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Los eventos de networking de Best Las Palmas me consiguieron mi
          trabajo de ensueño antes de graduarme."
        tagline: Testimonio 2
        subtitle: 'Carlos Mendoza, Estudiante de Ingeniería'
        text: >-
          Gracias a las conexiones que hice aquí, conseguí prácticas en una
          startup increíble y ahora tengo una oferta de trabajo full-time. ¡Best
          Las Palmas funciona!
        image:
          url: /images/img-placeholder-dark.png
          altText: Carlos Mendoza
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Aquí no solo estudias, vives experiencias que te marcan para toda la
          vida. ¡Es como una segunda familia!"
        tagline: Testimonio 3
        subtitle: 'Ana Rodríguez, Estudiante de Psicología'
        text: >-
          Los viajes, las fiestas, los proyectos colaborativos... Todo en Best
          Las Palmas está diseñado para que crezcas como persona mientras te
          diviertes al máximo.
        image:
          url: /images/person-placeholder-light.png
          altText: Ana Rodríguez
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: "Únete a la familia Best Las Palmas \U0001F3E0"
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Todo lo que necesitas para una experiencia universitaria épica
    items:
      - title: Eventos semanales
        tagline: Siempre activos
        subtitle: Nunca te aburrirás
        text: |
          Fiestas, talleres, charlas, torneos... ¡Siempre hay algo que hacer!
        image:
          url: /images/abstract-feature1.svg
          altText: Eventos estudiantiles
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Networking real
        tagline: Conexiones que importan
        subtitle: Tu futuro profesional
        text: >
          Conecta con empresas, startups y profesionales que pueden cambiar tu
          carrera.
        image:
          url: /images/abstract-feature2.svg
          altText: Networking profesional
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Comunidad increíble
        tagline: Tu nueva familia
        subtitle: Amistades para toda la vida
        text: |
          Conoce personas increíbles que comparten tus intereses y ambiciones.
        image:
          url: /images/abstract-feature1.svg
          altText: Comunidad estudiantil
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title:
      text: "¿Listo para unirte? \U0001F680"
      color: text-dark
      type: TitleBlock
    subtitle: Completa el formulario y comienza tu aventura
    text: |-
      Solo necesitamos algunos datos para conocerte mejor y enviarte toda la
      información sobre próximos eventos, oportunidades exclusivas y cómo
      formar parte activa de nuestra comunidad.
    actions: []
    media:
      fields:
        - name: name
          label: Nombre
          hideLabel: true
          placeholder: Tu nombre completo
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: tu.email@universidad.com
          isRequired: true
          width: full
          type: EmailFormControl
        - name: university
          label: Universidad
          hideLabel: true
          placeholder: ¿En qué universidad estudias?
          isRequired: true
          width: full
          type: TextFormControl
        - name: career
          label: Carrera
          hideLabel: true
          placeholder: ¿Qué carrera estudias?
          isRequired: true
          width: full
          type: TextFormControl
        - name: message
          label: Mensaje
          hideLabel: true
          placeholder: Cuéntanos por qué quieres unirte a Best Las Palmas
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: ¡Quiero unirme!
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: ¡Da el primer paso!
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Best Las Palmas - Asociación Estudiantil
  metaDescription: >-
    Únete a la asociación estudiantil más vibrante de Las Palmas. Eventos,
    networking, desarrollo personal y una comunidad increíble te esperan.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
