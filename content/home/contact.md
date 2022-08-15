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
  email: jerem.forest@gmail,com
  phone: 
  address:
    street:
    city: New Haven
    region: CT
    postcode: 
    country: United States
    country_code: US
  coordinates:
    latitude: 
    longitude:
  directions:
  office_hours:
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/jerem_forest'

design:
  columns: '2'
---
