---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

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
  address:
    street: Samelsonplatz 1
    city: Hildesheim
    postcode: '31141'
  coordinates:
    latitude: '52.134309111665985'
    longitude: '9.967693164540405'

design:
  columns: '2'
---
