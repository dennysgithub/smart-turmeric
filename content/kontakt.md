---
title: General enquiries
sections:
  - subtitle: lorem-ipsum
    content: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    actions: []
    image_alt: lorem-ipsum
    media_position: top
    media_width: fifty
    align: left
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: hero_section
  - type: form_section
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /tack-for-ditt-meddelande
    form_fields:
      - type: form_field
        input_type: text
        name: name
        default_value: Ditt namn
        is_required: true
      - type: form_field
        input_type: email
        name: email
        default_value: Din mejl
        is_required: true
      - input_type: tel
        name: Tele
        default_value: Ditt telefonnummer
        options: []
        is_required: true
        type: form_field
      - input_type: select
        name: Hur-vill-du-bli-kontaktad
        default_value: Hur vill du bli kontakad?
        options:
          - Telefon
          - Mejl
          - Spelar ingen roll
        is_required: true
        type: form_field
      - input_type: textarea
        name: Beskrivning
        default_value: 'Skriv kortfattat vad det gäller, tack.'
        options: []
        is_required: true
        type: form_field
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          Jag förstår att det här formuläret lagrar min inlämnade information så
          att jag kan kontaktas.
        is_required: true
    submit_label: Skicka
    align_vert: top
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image_opacity: 20
seo:
  type: stackbit_page_meta
  title: SEOmetoden | Kontakt
  description: >-
    Hör av dig för att se hur jag på seodennis.se kan hjälpa dig förbättra ditt
    kundflöde. 
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
layout: advanced
---
