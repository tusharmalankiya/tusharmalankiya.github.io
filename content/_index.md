---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    id: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Full-Stack Web Developer
          company: Mark91 Studio
          company_url: ''
          company_logo: mark91_studio_logo
          location: Surat
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Designing and implementing user-friendly web interfaces with a focus on responsive design.
              * Developing and managing server-side applications, databases, and APIs.
              * Collaborating with cross-functional teams to gather requirements and deliver high-quality software solutions.
              * Performing code reviews, debugging, and optimising web applications for performance and scalability.
              * Ensuring the security and integrity of web applications by applying best practices and industry standards.
              * Deploying the web applications.
        # - title: Professor of Semiconductor Physics
        #   company: University X
        #   company_url: ''
        #   company_logo: org-x
        #   location: California
        #   date_start: '2016-01-01'
        #   date_end: '2020-12-31'
        #   description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        # - certificate_url: https://cs50.harvard.edu/certificates/3d9b17d3-e91b-47a9-bca6-85c74a8d0f6d.png?size=letter
        #   date_end: ''
        #   date_start: '2024-07-03'
        #   description: ''
        #   icon: Harvard_University_shield
        #   organization: Harvard University
        #   organization_url: https://www.harvard.edu
        #   title: CS50's Understanding Technology
        #   url: ''
        # - certificate_url: https://www.udemy.com/certificate/UC-e0318fab-70a3-47b7-97f1-a9005d30c9f5/
        #   date_end: ''
        #   date_start: '2022-12-10'
        #   description: ''
        #   icon: udemy-icon
        #   organization: Udemy
        #   organization_url: https://www.udemy.com
        #   title: The Complete 2023 Web Development Bookcamp
        #   url: ''
        # - certificate_url: https://www.credential.net/54fbf673-761e-4496-a824-7842ceb86878/
        #   date_end: ''
        #   date_start: '2020-11-27'
        #   description: ''
        #   icon: startup
        #   organization: Startup India
        #   organization_url: https://www.startupindia.gov.in/
        #   title: Startup India Learning Program
        #   url: ''
        # - certificate_url: https://www.datacamp.com
        #   date_end: '2020-12-21'
        #   date_start: '2020-07-01'
        #   description: ''
        #   icon: datacamp
        #   organization: DataCamp
        #   organization_url: https://www.datacamp.com
        #   title: 'Object-Oriented Programming in R'
        #   url: ''
        - certificate_url: 'https://drive.google.com/file/d/1VvI9-DNRQBh5BpoCRqYvthtVhGPoD1Xv/view?usp=sharing'
          date_end: ''
          date_start: '2018-11-18'
          description: ''
          icon: NIT_Surat_Logo
          organization: Drishti, SVNIT
          organization_url: ''
          title: 2nd Place in the 'FLASH' of Grand Robo Prix Competition
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2019-02-23'
          description: ''
          icon: NIT_Surat_Logo
          organization: Sparsh, SVNIT
          organization_url: ''
          title: 2nd Place in Mobile Controlled Robotics Competition
          url: ''
    design:
      columns: '2'
  
  - block: accomplishments
    id: certifications
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certifications'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://cs50.harvard.edu/certificates/f68336ff-d0c1-4cbd-a90c-2612fd891b15.png?size=letter
          date_end: ''
          date_start: '2024-08-30'
          description: ''
          icon: Harvard_University_shield
          organization: Harvard University
          organization_url: https://www.harvard.edu
          title: CS50’s Introduction to Computer Science
          url: ''
        - certificate_url: https://cs50.harvard.edu/certificates/3d9b17d3-e91b-47a9-bca6-85c74a8d0f6d.png?size=letter
          date_end: ''
          date_start: '2024-07-03'
          description: ''
          icon: Harvard_University_shield
          organization: Harvard University
          organization_url: https://www.harvard.edu
          title: CS50's Understanding Technology
          url: ''
        - certificate_url: https://www.udemy.com/certificate/UC-e0318fab-70a3-47b7-97f1-a9005d30c9f5/
          date_end: ''
          date_start: '2022-12-10'
          description: ''
          icon: udemy-icon
          organization: Udemy
          organization_url: https://www.udemy.com
          title: The Complete 2023 Web Development Bootcamp
          url: ''
        - certificate_url: https://www.credential.net/54fbf673-761e-4496-a824-7842ceb86878/
          date_end: ''
          date_start: '2020-11-27'
          description: ''
          icon: upgrad-logo
          organization: upGrad
          organization_url: https://www.startupindia.gov.in/
          title: S. I. L. P.
          url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Robotics
          tag: Robotics
        - name: Full-Stack
          tag: Full-Stack
        - name: Others
          tag: Others
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
    # content:
    #   title: Gallery
    #   subtitle: ''
    #   text: |-
    #     {{< gallery album="demo" >}}
    # design:
    #   columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
      email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     # Choose a map provider in `params.yaml` to show a map from these coordinates
  #     coordinates:
  #       latitude: '37.4275'
  #       longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
