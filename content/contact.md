---
title: Contact
sections:
  - type: section_contact
    template: section_contact
    section_id: contact
    title: Contact
    content: >
      Send a general enquiry, question, report an error, or even suggest a
      collaboration. 
    background: gray
    form_id: contactForm
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: Name
        is_required: true
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: Email
        is_required: true
      - type: form_field
        template: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Enquiry
          - Other
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
layout: landing
---
