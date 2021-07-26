---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¡Hola! Si deseas ponerte en contacto puedes rellenar el siguiente
      formulario o enviarme un correo a andiparodi.20@gmail.com.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Correo
        default_value: Tu dirección de correo
        is_required: true
      - input_type: select
        name: Asunto
        label: Asunto
        default_value: Selecciona un asunto
        options:
          - Contacto
          - Error o bug en el sitio
          - Idea para el sitio
          - Otro
      - input_type: textarea
        name: mensaje
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario esta almacenando mi información enviada
          para que puedan ser contactados.
    submit_label: Enviar
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
