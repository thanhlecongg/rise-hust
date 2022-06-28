---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: thanghq@soict.hust.edu.vn
  phone: +84 (024) 3868 1912
  address:
    street: No. 1 Dai Co Viet, Hai Ba Trung, Hanoi, Vietnam
    city: Hanoi
    region: Hanoi
    postcode: '10999'
    country: Vietnam
    country_code: VN
  coordinates:
    latitude: '15.03"'
    longitude: '37.5684'
  directions: Room 210, Building C1
  # appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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

design:
  columns: '1'
---
