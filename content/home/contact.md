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
  email: jzhang105@mgh.harvard.edu
 # phone: 
  address:
    street: 149 13th St
    city: Charlestown
    region: MA
    postcode: '02129'
    country: United States
    country_code: US
  coordinates:
    latitude: '42.3782' 
    longitude: '-71.0501'
  directions: Enter Athinoula A. Martinos Center for Biomedical Imaging and take the stairs to office 2626 on Floor 2
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/jingandzhang'


design:
  columns: '2'
---
