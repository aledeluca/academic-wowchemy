---
# Leave the homepage title empty to use the site title
title: Alessandro De Luca
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: alessandro-de-luca
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Researcher
          company: Univ. Napoli Federico II
          company_url: 'http://www.unina.it'
          company_logo: Unina_LogoBlu
          location: Italy
          date_start: '2010-12-28'
          date_end: ''
          description: Includes teaching assistance and tutoring duties.
        - title: Adjunct Professor
          company: Univ. Napoli Federico II
          company_url: 'http://www.unina.it'
          location: Italy
          date_start: '2012-01-01'
          date_end: ''
          description: |2-
              Classes taught:

              * Elements of Theoretical Computer Science
              * Theory of Codes
              * Databases (lab), 2012–2019
              * Information Theory, 2013–2019
              
        - title: Postdoc (_Tutkijatohtori_ )
          company: University of Turku
          company_url: 'https://www.utu.fi'
          location: Finland
          date_start: '2010-10-01'
          date_end: '2012-02-29'
          description: |-
            Full-time in 2010, part-time afterwards; within the
              [FiDiPro group](http://www.math.utu.fi/projects/fundim/fidipro/).
        - title: Postdoc (_Stagiaire postdoctoral_ )
          company: UQAM
          company_url: 'https://www.uqam.ca'
          location: 'Montréal, Canada'
          date_start: '2009-09-21'
          date_end: '2010-09-20'
          description: 'At [LaCIM](http://lacim.uqam.ca/).'
        - title: Postdoc (_Assegnista di ricerca_)
          company: Univ. Napoli Federico II
          company_url: 'http://www.unina.it'
          location: Italy
          date_start: '2008-06-01'
          date_end: '2009-05-31'
          description: ''
    design:
      columns: '2'
  # - block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  # - block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
      columns: '2'
---
