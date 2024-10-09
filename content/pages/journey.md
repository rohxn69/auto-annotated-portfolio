---
type: PageLayout
title: My Journey
sections:
  - type: HeroSection
    title: 2016 Youtube Vlogger
    subtitle: >-
      Ah, the good old days when I started making YouTube videos and was
      influenced by Jake Paul and Logan Paul. I still get cringe attacks if I
      watch that video. Hahaha!
    text: >-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
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
  - type: ContactSection
    title: Got an interesting project? Tell me more...
    text: ''
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          width: 1/2
          isRequired: false
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
      submitLabel: "Submit \U0001F680"
      elementId: sign-up-form
      styles:
        submitLabel:
          textAlign: center
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
