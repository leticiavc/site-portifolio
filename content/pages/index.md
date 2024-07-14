---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Unblock your team boost your time to production
      color: text-light
      type: TitleBlock
    subtitle: Subtitle goes here
    text: >
      A Netlify Create website is a git repo that you own. Every code commit is
      instantly reflected in the visual editor and since every visual edit is a
      git commit, git workflows and collaboration just work.
    actions:
      - label: Baixar Currículo
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-light
      type: Badge
    elementId: ''
    colors: bg-dark-fg-light
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
      text: Experiência Acadêmica
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Concluídas e Cursando
    items:
      - type: FeaturedItem
        title: UniFECAF
        subtitle: 2023-2025
        text: |
          Análise e Desenvolvimento de Sistemas
        actions: []
        elementId: null
        colors: bg-neutral-fg-dark
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
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/Novo Projeto (11).png
          styles:
            self:
              borderRadius: x-large
      - title: Senac
        subtitle: 2016-2019
        text: >
          Bacharelado em Design - Linha de fomação específica em **Design
          Digital**
        image:
          url: /images/Novo Projeto (9).png
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
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
      - title: Senac
        subtitle: 2014-2015
        text: |
          Curso Técnico - **Técnico em Multimídia**
        image:
          url: /images/Novo Projeto (9).png
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
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
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
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
  - subtitle: Softwares
    images:
      - url: /images/Novo Projeto (1).png
        altText: Figma logo
        type: ImageBlock
      - url: /images/Novo Projeto (6).png
        altText: Blender logo
        type: ImageBlock
      - url: /images/Novo Projeto (5).png
        altText: Illustrator logo
        type: ImageBlock
      - url: /images/Novo Projeto (2).png
        altText: Photoshop logo
        type: ImageBlock
      - url: /images/Novo Projeto (3).png
        altText: After Effects logo
        type: ImageBlock
      - url: /images/Novo Projeto (4).png
        altText: Premiere Pro logo
        type: ImageBlock
      - url: /images/Novo Projeto (7).png
        altText: Procreate logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
    title:
      type: TitleBlock
      text: Habilidades
      color: text-dark
      styles:
        self:
          textAlign: center
  - title:
      text: Letícia Vieira Caçador
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Um pouco sobre mim
    text: >
      Olá! Sou uma jovem apaixonada por design e tecnologia, com uma trajetória
      acadêmica que reflete minha busca constante por conhecimento e novas
      habilidades. Iniciei minha jornada com uma graduação em Design Digital,
      onde desenvolvi competências avançadas em ferramentas como Figma,
      Photoshop e Ilustrador, fundamentais para criar interfaces intuitivas e
      visualmente impactantes para os usuários


      Atualmente, estou expandindo meus horizontes acadêmicos com uma segunda
      graduação em Análise e Desenvolvimento de Sistemas, o que me proporciona
      ter um bom entendimento em programação e a capacidade de integrar o design
      com tecnologias atuais.


      Minha experiência profissional como Web Designer tem sido gratificante,
      permitindo-me aplicar meus conhecimentos em UI/UX Design para desenvolver
      projetos que impacta diretamente os usuários. Além disso, venho
      desenvolvendo habilidades cada vez mais para acrescentar as interfaces
      visualmente como habilidades em Blender para criação de elementos 3D e
      habilidades  em edição de vídeo e efeitos especiais.
    badge:
      label: ''
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
      text:
        textAlign: center
    type: GenericSection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
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
      text: Business Consulting
      color: text-dark
      type: TitleBlock
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: This is a badge
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
    title:
      type: TitleBlock
      text: Recomendações
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Direto do Linkedin
    items:
      - title: >-
          “A Letícia é uma excelente profissional. Sempre dedicada em tudo que
          faz. Muito criativa, e sempre disposta a fazer o seu melhor. Ágil,
          dedicada e eficiênte nas entregas.”
        tagline: Em 15 de setembro de 2023
        subtitle: 'Janaína Ricciardi,Proxy Midia'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
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
          "Trabalho com a Leticia a cerca de 3 anos e ela demonstrou ser uma
          excelente profissional. Extremamente talentosa e ágil na criação e
          desenvolvimento de todo tipo de material, tanto online como impresso.
          Além de ser dedicada, criativa e interessada em atender a área da
          melhor maneira. As suas entregas são rápidas e feitas com muita
          eficiência."
        tagline: Em 14 de setembro de 2023
        subtitle: 'Karolina Sobral, Proxy Midia'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
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
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Featured items section subtitle
    items:
      - title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder Image
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
      - title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify Create site.
        image:
          url: /images/abstract-feature2.svg
          altText: Placeholder image
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
      - title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: >
          Learn from the tutorial and build your first awesome Netlify Create
          site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder image
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
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
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
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
