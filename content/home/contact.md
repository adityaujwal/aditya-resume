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
  email: itsadityaujwal@gmail.com
  #phone: +91 7738136591
  #address:
  #  street: A1301, Melodia, Gandhi Path West
   # city: Jaipur
   # region: Rajasthan
   # postcode: '302021'
   # country: India
   # country_code: IN
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://www.linkedin.com/in/aditya-ujwal-9a8529242/'
    
design:
  columns: '2'
---
