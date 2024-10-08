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

  # - block: markdown
  #   id: books
  #   content:
  #     title: Books
  #     subtitle:
  #     text: |-
  #       In the *The New Economic Populism: How States Respond to Economic Inequality* ([Oxford](https://global.oup.com/academic/product/the-new-economic-populism-9780190671013?cc=us&lang=en&) | [Amazon](https://www.amazon.com/New-Economic-Populism-Respond-Inequality/dp/0190671017)), we argue that the U.S. government’s failure to address rising income inequality should not be very surprising since federal inaction in the face of emerging economic problems is the norm in American history. The states led the fight against new economic problems during the Progressive Era and Great Depression, and it is likely that we will once again have to rely on the states to address today’s massive gap between the rich and the poor. We show that the public is cognizant of rising inequality and that this growing awareness is associated with more egalitarian political and policy changes. In contrast to the prevailing pessimism regarding income inequality, we suggest that if history is a guide these incipient state actions to reduce inequality are likely to spread to other states and even the federal government in the coming decades. 
        
  #       The New Economic Populism is [winner of the 2018 Virginia Gray Best Book Award](https://www.apsanet.org/STAFF/Staff-Page-dev/Membership-Workspace/Organized-Sections/Organized-Section-Awards/Organized-Section-Awards/Section-22#virginiagray). This award is given by the American Political Science Association State Politics and Policy Section to the best political science book published on the subject of U.S. state politics or policy in the preceding three calendar years.
  #   design:
  #     columns: '2'

  - block: collection
    id: books
    content:
      title: Books
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
 
  - block: collection
    id: research
    content:
      title: Recent Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
      count: 10
    design:
      columns: '2'
      view: citation
  
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-        
        [R/RStudio for Political Science tutorial]({{< ref "/post/rtutorial" >}}) for my POLS 300 students.

        My **Senior Capstone Paper** (POLS 487) advisees can download a copy of the [Paper Plan and Guidelines](uploads/CapstoneProjectSched.pdf).
        
        **Registered students** can find course materials on [eCampus](https://ecampus.wvu.edu/). 

        ---
        
        I am an instructor for the following courses at WVU:

        - State and Local Government (POLS 220)
        - Empirical Political Analysis (POLS 300)
        - The Politics of Economic Policy (POLS 334)
        - Intro. to Political Research (POLS 600)
        - Advanced Quantitative Analysis (POLS 603)
        
        Past courses:
        - American Government
        - The Politics of Economic Inequality
        - The American Presidency
        - Research Methods (grad)
        - Research Design and Analysis (grad)
        - The Legislative Process
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
