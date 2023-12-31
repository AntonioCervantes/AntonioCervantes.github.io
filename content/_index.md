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
        - title: Forest Canopy Wildfire Turbulence
          company: Boundary Layers & Turbulence Lab, UC Irvine
          company_url: https://faculty.sites.uci.edu/banerjeelab/
          company_logo: uci_logo
          location: ''
          date_start: '2023-09-01'
          date_end: ''
          description: |2-
              * Research the impact of forest canopy heterogeneity on atmospheric flows and wildfires
              * Validate PALM LES codes with experimental velocity data from the Amazon rainforest
              * Simulate flows through forest canopy gaps of various sizes
        - title: Wildfire Ember Transport
          company: Thermo-Fluids compleXity Lab, SJSU
          company_url: https://www.tfx-lab.com/
          company_logo: sjsu
          location: ''
          date_start: '2022-02-01'
          date_end: '2023-05-01'
          description: |2-
              * Investigated the influence of turbulence intensity on wildfire ember (firebrand) landing distribution for an improved understanding of spot fire generation and wildfire spread
              * Conducted large eddy simulation (LES) of channel flow at several turbulence intensities using high-fidelity CFD codes
              * Created a data visualization pipeline for statistical analysis of particle landing distribution
              * Developed novel integration of firebrand transport with wildfire model for full physics spot fire generation simulations
        - title: Wildfire Bio-Aerosol Transport
          company: Thermo-Fluids compleXity Lab, SJSU
          company_url: https://www.tfx-lab.com/
          company_logo: sjsu
          location: ''
          date_start: '2021-09-01'
          date_end: '2022-09-01'
          description: |2-
              * Developed numerical DEM simulation of more than 5 million bio-aerosols to understand deposition of pathogen-laden particles during a wildfire event for an NSF-funded research project
              * Leveraged Python acceleration and parallelization libraries to optimize code for a 99% increase in computation speed
              * Created Python functions for data-driven particle generation at fire locations for improved physics
              * Developed processing tools for large data visualizations and animations of more than 100 million data points
              * Collaborated with an interdisciplinary team to publish a novel biological emissions factor research paper
    design:
      columns: '2'
  - block: accomplishments
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
        - certificate_url: ''
          date_end: '2024-06-01'
          date_start: '2023-09-01'
          description: Fellowship for the 23/24 school year where I am required to conduct 3 teaching assitantships during my PhD at UCI, and develop new skills and gain mentorship in teaching.
          icon: uci_logo
          organization: UC Irvine, US Department of Education
          organization_url: ''
          title: Graduate Fellowship in Areas of National Need (GAANN)
          url: ''
        - certificate_url: ''
          date_end: '2023-05-01'
          date_start: '2022-08-01'
          description: Recieved scholarship which required completion of master's thesis by the end of the Spring 2023 semester and poster presentation in the annual College of Engineering 2023 Student Showcase and Celebration. [See poster](uploads/Davidson_Scholar_CoE_Showcase_Poster-QR.pdf)
          icon: sjsu
          organization: Charles W. Davidson College of Engineering, SJSU
          organization_url: https://www.sjsu.edu/engineering/index.php
          title: Davidson Student Scholar
          url: ''
        - certificate_url: ''
          date_end: '2023-05-01'
          date_start: '2022-08-01'
          description: ''
          icon: sjsu
          organization: Charles W. Davidson College of Engineering, SJSU
          organization_url: https://www.sjsu.edu/engineering/index.php
          title: Dierks-Morgan Scholarship
          url: ''
        - certificate_url: ''
          date_end: '2022-07-01'
          date_start: '2022-05-01'
          description: Competed in the Summer 2022 Autodesk Instructable design challenge where I designed an aerodynamic upgrade package for my RC car which improved its top speed. My entry placed as a finalist in the Runner Up category. [See my entry here](https://www.instructables.com/RC-Car-Upgrade-Using-3D-Printing/)
          icon: 
          organization: Autodesk Instructables
          organization_url: https://www.instructables.com/
          title: Digital Fabrication Student Design Challenge Winner
          url: https://www.instructables.com/contest/digifab2022/
    design:
      columns: '2'
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
        - name: Wildfires
          tag: Wildfires
        - name: Turbulence
          tag: Turbulence
        - name: CFD
          tag: CFD
        - name: Machine Learning
          tag: Machine Learning
        - name: Robotics
          tag: Robotics
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
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
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me if you have any questions!
      # Contact (add or remove contact options as necessary)
      email: aqcervan@uci.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
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
