---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
    # content:
      # title: Skills
      # items:
        # - name: R
          # description: 90%
          # icon: r-project
          # icon_pack: fab
        # - name: Statistics
          # description: 100%
          # icon: chart-line
          # icon_pack: fas
        # - name: Photography
          # description: 10%
          # icon: camera-retro
          # icon_pack: fas
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
        - title: Assistant Professor
          company: University of Cassino and Southern Lazio
          company_url: 'https://www.unicas.it/'
          company_logo: org-unicas
          location: Cassino, Italy
          date_start: '2021-03-01'
          date_end: ''
          description: |2-

              * Research on beyond-5G physical layer technologies: Massive MIMO, reconfigurable intelligent surfaces, mmWave communications.
              * Course director, lecturer and examiner of the course “Digital signal processing”, Master of Science in Telecommunications Engineering (LM-27).
        - title: Coordinator of the **Meta Wireless** Early Stage Researchers
          company: National Inter-University Consortium for Telecommunications
          company_url: 'https://www.cnit.it/'
          company_logo: org-cnit
          location: Cassino, Italy
          date_start: '2021-09-01'
          date_end: ''
          description: |-
              [**Meta Wireless**](https://h2020-msca-itn-metawireless.cnit.it) is multi-partner European Training Network project, within the framework of the H2020 Marie Sklodowska-Curie Innovative Training Networks.
        - title: Consultant
          company: Ericsson Research
          company_url: 'https://www.ericsson.com'
          company_logo: org-ericsson
          location: Linköping, Sweden
          date_start: '2018-10-26'
          date_end: '2020-10-31'
          description: |2-

              * Development of novel signal processing algorithms and communication protocols for distributed massive MIMO systems.
              * Cross-layer design of massive MIMO systems and wake-up receivers.
        - title: Doctoral Student
          company: Linköping University
          company_url: 'https://www.liu.se'
          company_logo: org-liu
          location: Linköping, Sweden
          date_start: '2015-10-26'
          date_end: '2020-10-31'
          description: |2-

              * Analysis, design and optimization of smart and distributed device-centric cellular architectures with emphasis on 5G large-scale multiple-antenna technologies. 
              * From 2018 to 2020, teaching assistant for the courses “Wireless Communications” and “Multiple Antenna Communications”, Master of Science in Engineering and Computer Sciences. In charge of tutorial and lab sessions. Examiner of laboratory works.
              * Ph.D. thesis: ["Cell-Free Massive MIMO: Scalability, Signal Processing and Power Control"](http://www.diva-portal.org/smash/record.jsf?pid=diva2:1448945).
        - title: Researcher
          company: Ericsson Research
          company_url: 'https://www.ericsson.com'
          company_logo: org-ericsson
          location: Linköping, Sweden
          date_start: '2015-10-26'
          date_end: '2018-10-25'
          description: |2-

              * Development of novel signal processing algorithms and communication protocols for 5G NR systems.
              * Development of flexible, cost-efficient architectures for practical distributed massive MIMO deployments. Co-inventor of the [Ericsson Radio Stripes](https://www.ericsson.com/en/blog/2019/2/radio-stripes).
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
  # - block: tag_cloud
    # content:
      # title: Popular Topics
    # design:
      # columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please get in contact if you are interested in discussing research ideas, talking about data or code, or have any questions about my research.
      # Contact (add or remove contact options as necessary)
      email: giovanni.interdonato.phd@gmail.com
      # phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: Via Gaetano Di Biasio 43
        city: Cassino
        region: FR
        postcode: 'I-03043'
        country: Italy
        country_code: IT
      directions: Enter Building A and take the stairs to Office 102 on Floor 1, in front of the lecture hall 
      office_hours:
        - 'Tuesday 10:00 to 12:00'
        - 'Thursday 10:00 to 12:00'
      # contact_links:
        # - icon: twitter
          # icon_pack: fab
          # name: DM Me
          # link: 'https://twitter.com/Twitter'
        # - icon: skype
          # icon_pack: fab
          # name: Skype Me
          # link: 'skype:echo123?call'
        # - icon: video
          # icon_pack: fas
          # name: Zoom Me
          # link: 'https://zoom.com'
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
      # Map
      coordinates:
          latitude: '41.48827492802745'
          longitude: '13.825776695186512'
    design:
      columns: '2'
---
