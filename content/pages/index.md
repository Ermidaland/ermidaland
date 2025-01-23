---
type: PageLayout
title: Terreno
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/traseira-moradia.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 30
sections:
  - type: TextSection
    colors: colors-c
    variant: variant-a
    title: Terreno com Projeto Aprovado e Pronto para Construção
    subtitle: Matosinhos
    text: >
      **Com tudo preparado para dar início à construção da sua nova
      residência.**
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: HeroSection
    title: Matosinhos
    subtitle: São Mamede Infesta - Zona de Ermida
    actions:
      - type: Button
        label: 180.000 €
        altText: ''
        url: ''
        showIcon: false
        icon: arrowRight
        iconPosition: left
        style: primary
        elementId: ''
      - type: Link
        label: 210 m2
        altText: ''
        url: ''
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/foto-real-terreno.png
      altText: terreno são mamede infesta - matosinhos
      caption: terreno para venda
      elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: >
      Terreno com projeto aprovado para construção de uma moradia unifamiliar de
      tipologia T4, de duas frentes, formada por rés do chão, primeiro andar e
      aproveitamento do vão de telhado, situado na Rua Aquilino Ribeiro, zona de
      Ermida, em São Mamede de Infesta.Esta é a oportunidade ideal para quem
      procura um imóvel onde possa construir uma moradia de alta qualidade e com
      todos os detalhes já planeados. Apresentamos um terreno com projeto
      aprovado para uma moradia unifamiliar, desenhada para oferecer conforto,
      funcionalidade e elegância.
  - type: TextSection
    colors: colors-c
    variant: variant-b
    title: Projeto Moderno e Funcional
    subtitle: ''
    text: >+
      *   Aquitetura contemporânea, com linhas modernas e uma perfeita
      integração na paisagem envolvente.


      *   3 quartos amplos, incluindo uma suíte principal com closet e varanda.


      *   Sala de estar espaçosa, ideal para momentos de lazer e convívio.


      *   Cozinha de conceito aberto, prática e adaptada ao ritmo de vida
      moderno.


      *   Jardim privativo e área de convívio ao ar livre.

    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: MediaGallerySection
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/frente-moradia-ampliada.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/traseira-moradia.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/foto 5.jpg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/foto 7.jpeg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: HeroSection
    title: Localização privilegiada
    subtitle: Zona da Ermida
    actions: []
    media:
      type: ImageBlock
      url: /images/google-maps2.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: >
      Situado numa área calma e de fácil acesso, perto de escolas, comércio e
      serviços essenciais.


      A poucos minutos das principais vias de acesso, garantindo comodidade no
      seu dia a dia.
  - type: MediaGallerySection
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/planta-com-aproveitamento-sotao.png
        altText: Image one
        caption: Image one caption
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: ContactSection
    title: Contacte-nos
    text: |
      Tem interesse?
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: ''
          label: ''
          hideLabel: false
          placeholder: Nome
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: ''
          label: ''
          hideLabel: false
          placeholder: Email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: ''
          label: ''
          hideLabel: true
          placeholder: Mensagem
          width: full
          isRequired: true
      submitLabel: Submeter
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/foto 2.png
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
metaTitle: Terreno à venda Matosinhos
socialImage: /images/frente-moradia-ampliada.png
metaDescription: Terreno à venda São Mamede Infesta
---
