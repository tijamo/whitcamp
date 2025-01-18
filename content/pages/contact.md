---
type: PageLayout
title: Details
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
    actions: []
    media:
      type: ImageBlock
      url: /images/grass.jpg
      altText: Dope design preview
      styles:
        self:
          borderWidth: 0
          borderStyle: none
          borderRadius: none
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: col
        justifyContent: center
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
  - type: GenericSection
    title:
      type: TitleBlock
      text: Contact Us
      color: text-dark
    subtitle: ''
    text: "If you have any booking queries, telephone or email Joyce (<bookings@whitcamp.co.uk>).\n\nFor more general queries, email\_<committee@whitcamp.co.uk>.\n"
    actions: []
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: '-reverse'
        padding:
          - pt-6
          - pr-6
          - pb-6
          - pl-6
  - type: GenericSection
    title:
      type: TitleBlock
      text: Contact Us
      color: text-dark
    subtitle: ''
    text: "If you have any booking queries then please telephone or email Joyce (<bookings@whitcamp.co.uk>).\n\nFor more general queries please use the form to the right or email\_<committee@whitcamp.co.uk>.\n"
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
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
    badge:
      type: Badge
      label: GET IN TOUCH
      color: text-primary
    colors: bg-light-fg-dark
slug: /contact
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
