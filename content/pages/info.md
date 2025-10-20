---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/generated-image (6).png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 60
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      I am a Mechatronics engineer with over three years of hands-on experience
      in CAD, GD\&T, and PLC programming, specializing in the design,
      visualization, and coordinated development of machinery, fixtures, and
      ergonomic workstations using integrated mechatronic systems. My technical
      background is complemented by a rigorous commitment to safety and quality,
      evidenced by my role at Bosch where I led the establishment of new
      machines, developed advanced fixtures, and ensured compliance with robust
      safety protocols across production environments.


      Currently, I am pursuing an MSc in Engineering with Management
      (Intelligent Manufacturing) at the University of Bristol, where I am
      deepening my expertise in strategy, risk management, and organizational
      leadership. This dual focus has empowered me to develop risk mitigation
      frameworks for manufacturing transformations and to bridge the gap between
      innovative engineering and effective business management.


      I am passionate about joining consulting because it allows me to leverage
      both my technical proficiency and strategic mindset to solve
      multidimensional problems for clients. Consulting excites me as it offers
      the chance to engage with complex decision-making processes, understand
      how engineering innovations impact business and financial outcomes, and
      contribute to the development of holistic solutions that deliver
      measurable value. I aspire to be at the forefront of interdisciplinary
      teams, influencing tactical choices and guiding organizations through
      technological change, operational efficiency improvements, and the
      realization of sustainable growth.

    media:
      type: ImageBlock
      url: /images/generated-image (3).png
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
    actions: []
  - type: FeaturedItemsSection
    subtitle: 'You can find me here:'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        elementId: ''
        styles:
          self:
            textAlign: left
        actions:
          - type: Link
            label: Mail
            altText: ''
            url: 'mailto:work.utsavgopalka@gmail.com'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * freelance @freelance.me

          **2018-2021**

          * fullstack at this startup

          **2015**

          * senior front-end at this place

          **2013**

          * intern developer at a big company

          **2011**

          * flipping burgers
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2015-2018**

          * ba computer sciense at a semi fancy school

          **2014**

          * react certificate somewhere

          **2011**

          * my highschool
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
