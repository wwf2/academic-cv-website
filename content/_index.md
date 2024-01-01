---
# Leave the homepage title empty to use the site title
title: 'William Franko'
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: markdown
    id: books
    content:
      title: Books
      subtitle:
      text: |
      In the New Economic Populism How States Respond to Economic Inequality (Oxford | Amazon), we argue that the U.S. government’s failure to address rising income inequality should not be very surprising since federal inaction in the face of emerging economic problems is the norm in American history. The states led the fight against new economic problems during the Progressive Era and Great Depression, and it is likely that we will once again have to rely on the states to address today’s massive gap between the rich and the poor. We show that the public is cognizant of rising inequality and that this growing awareness is associated with more egalitarian political and policy changes. In contrast to the prevailing pessimism regarding income inequality, we suggest that if history is a guide these incipient state actions to reduce inequality are likely to spread to other states and even the federal government in the coming decades.  
      The New Economic Populism is winner of the 2018 Virginia Gray Best Book Award. This award is given by the American Political Science Association State Politics and Policy Section to the best political science book published on the subject of U.S. state politics or policy in the preceding three calendar years.
      # <img style="text-align: center; width: 80%; height: auto" src="img/BookCover2.jpg" alt="Book Cover 2"/>
      # <br/>
    design:
      columns: '2'
  
  - block: markdown
    id: cv
    content:
      title: Curriculum Vitae
      text: Download a [PDF copy of my CV](uploads/Franko_CV.pdf)
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: william.franko@mail.wvu.edu
      phone: (304) 554-9838
      appointment_url: ''
      address:
        street: Department of Political Science, 316 Woodburn Hall 
        city: Morgantown
        region: WV
        postcode: '26506'
        country: United States
        country_code: US
      directions: 
      office_hours:
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: ''
        longitude: ''  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
