---
title: Fale comigo
sections:
  - type: hero_section
    title: Fale comigo
    subtitle: >-
      Preencha o formulário abaixo e entrarei em contato em breve.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
     
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Seu nome completo
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
        default_value: Deixe aqui uma mensagem
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
  title: Fale comigo
  description: This is the contact page
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: Fale comigo
      keyName: property
    - name: og:description
      value: This is the contact page
      keyName: property
    - name: twitter:card
      value: summary
    - name: twitter:title
      value: Fale comigo
    - name: twitter:description
      value: This is the contact page
layout: advanced
---
