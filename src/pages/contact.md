---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Skorzystaj z formularza poniżej
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Imię
        default_value: Twoje imię
        is_required: true
      - input_type: email
        name: email
        label: E-mail
        default_value: Twój adres e-mail
        is_required: true
      - input_type: select
        name: subject
        label: Tytuł
        default_value: Please select
        options:
          - Zapytanie ofertowe
          - Inne
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
