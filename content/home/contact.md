---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: true


# Order that this section appears on the page.
weight: 130

title: Contact


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
  email: jing.zhang@uci.edu
 # phone: 
  address:
    street: SSL 380, UCI
    city: Irvine
    region: CA
    postcode: '92617'
    country: United States
    country_code: US
  coordinates:
    latitude: '33.6405'
    longitude: '-117.8443'
  directions: Enter SSL and take the stairs to Office 380 on Floor 3
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/jingandzhang'


design:
  columns: '2'
---
