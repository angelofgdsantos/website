---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: angelofgdsantos@gmail.com
  address: 4800 Calhoun Rd, Houston, TX 77004
    street: 4800 Calhoun Rd
    city: Houston
    region: TX
    postcode: '77004'
    country: United States
    country_code: US
  #appointment_url: 'https://calendly.com'
  #contact_links:
    #- icon: twitter
    #  icon_pack: fab
    #  name: DM Me
    #  link: 'https://twitter.com/Twitter'
    #- icon: video
    #  icon_pack: fas
    #  name: Zoom Me
    #  link: 'https://zoom.com'

design:
  columns: '2'
---
