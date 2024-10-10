---
type: PageLayout
title: Empty page
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: This in an empty page
    subtitle: The section subtitle
    text: >
      <h2>How did I host this website for free?</h2>


      <hr style="border: 2px double white; width: 75%; margin: 10px 0;">


      <p style="font-size: 16px;">
          Step 1: Buy a domain. Try <i>spaceship.com</i>. It's cheap, and we’re all on a budget.
      </p>

      <p style="font-size: 16px;">
          Step 2: Sign up for Netlify. It’s free, and who doesn’t love free stuff?
      </p>

      <p style="font-size: 16px;">
          Step 3: Make a GitHub account to store your files. It sounds fancy, but it’s basically free storage.
      </p>

      <p style="font-size: 16px;">
          Step 4: Pick a template and customize it... or don’t. Up to you.
      </p>

      <p style="font-size: 16px;">
          Step 5: Point your domain to Netlify. Basically, just make sure it works!
      </p>


      <p style="font-size: 16px;">And boom! Your site is live. Minimal effort,
      maximum result.</p>


      <p style="font-size: 16px;">Still confused? I can help—just ask!</p>


      <a href="mailto:rohan@rohxn.com" style="text-decoration: none;">
          <button style="padding: 10px 20px; background-color: #4CAF50; color: white; border: none; border-radius: 5px; cursor: pointer;">
              Email Me
          </button>
      </a>


      <hr>
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
