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
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
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
  - type: GenericSection
    title:
      type: TitleBlock
      text: Letícia Vieira Caçador
      color: text-primary
      styles:
        self:
          textAlign: center
          fontWeight: 700
    subtitle: Um pouco sobre mim
    text: >
      **Olá! Sou uma jovem apaixonada por design e tecnologia,** com uma
      trajetória acadêmica que reflete minha busca constante por conhecimento e
      novas habilidades. Iniciei minha jornada com uma graduação em Design
      Digital, onde desenvolvi competências avançadas em ferramentas como Figma,
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
    actions:
      - type: Button
        label: Ver Cursos
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        showIcon: true
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
        fontStyle: italic
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/images (1).jfif
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
    title:
      type: TitleBlock
      text: Projetos/Cases de estudos
      color: text-dark
      styles:
        self:
          textAlign: center
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
          url: /images/avatar2.svg
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
          url: /images/avatar1.svg
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
