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
      captcha: true

  # Contact details (edit or remove options as required)
  email: contact.scheduling.cc@gmail.com
  address:
    street: 12 rue Marie Curie CS 42060
    city: Troyes
    postcode: '10004'
    country: France
    country_code: FR
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM US
      link: 'https://twitter.com/schedulingcc'

design:
  columns: '2'
---
