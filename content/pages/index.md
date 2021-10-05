---
title: Home
sections:
  - type: hero_section
    title: Olá, meu nome é Patrícia, juntos podemos encontrar o seu melhor.
    subtitle: >-
      Acolher e transformar. Para você que está preparado, quer mudar, e busca ajuda: conte comigo! Buscaremos e investigaremos a fundo as bases e origens, analisando o todo, para possibilitar uma verdadeira transformação. Qualidade de vida, equilíbrio, propósito e bem-estar. Harmonia e Gratidão.
    actions:
      - label: Fale comigo
        url: /contact
        style: primary
    image: images/hero.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: Meus Serviços
    subtitle: O que eu faço?
    features:
      - title: Orientação Terapêutica Online
        subtitle: Um subtitulo aqui
        content: >-
          Algum texto que faça sentido com pelo menos 100 palavras
        # actions:
        #   - label: See Writing Samples
        #     url: /faq
        #     style: primary
        #     has_icon: true
        #     icon: arrow-right
        #     icon_position: right
        image: images/saude-mental.png
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Terapia Online
        subtitle: Um subtitulo aqui
        content: >-
          Algum texto que faça sentido com pelo menos 100 palavras
        # actions:
        #   - label: Learn More
        #     url: /about
        #     style: secondary
        #     has_icon: true
        #     icon: arrow-right
        #     icon_position: right
        image: images/aconselhamento-online.png
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Programa de Apoio Emocional
        subtitle: Um subtitulo aqui
        content: >-
          Algum texto que faça sentido com pelo menos 100 palavras
        # actions:
        #   - label: See Past Work
        #     url: /faq
        #     style: primary
        #     has_icon: true
        #     icon: arrow-right
        #     icon_position: right
        image: images/depressao.png
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
      - title: Terapia de Casal Online
        subtitle: Um subtitulo aqui
        content: >-
          Algum texto que faça sentido com pelo menos 100 palavras
        # actions:
        #   - label: See Past Work
        #     url: /faq
        #     style: primary
        #     has_icon: true
        #     icon: arrow-right
        #     icon_position: right
        image: images/feat1.png
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: form_section
    content: >-
      ## Vamos conversar?


      Se você quiser mais informações sobre meus serviços, por favor
      Contacte-me através do formulário abaixo.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Seu nome
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Seu melhor email
        is_required: true
      - input_type: tel
        name: phone
        label: Telefone
        default_value: Seu telefone
        is_required: true
      - input_type: textarea
        name: message
        label: Mensagem
        default_value: Deixe uma mensagem
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que este formulário está armazenando minhas informações enviadas para que eu possa ser contatado.
        is_required: true
    submit_label: Enviar
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Patrícia Soares
  description: The preview of the Personal theme
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: Patrícia Soares
      keyName: property
    - name: og:description
      value: The preview of the Personal theme
      keyName: property
    - name: og:image
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: twitter:card
      value: summary_large_image
    - name: twitter:title
      value: Patrícia Soares
    - name: twitter:description
      value: The preview of the Personal theme
    - name: twitter:image
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
