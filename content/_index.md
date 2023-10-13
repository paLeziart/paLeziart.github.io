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
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
        - title: Postdoctoral Fellow
          company: Laboratory of Analysis and Architecture of Systems
          company_url: https://www.laas.fr/public/en/gepetto
          company_logo: org-gc
          location: Toulouse, France
          date_start: '2023-11-01'
          date_end: ''
          description: |2-
              My PostDoc has been been focused on getting the Sassa quadruped robot ready for the IEEE ICRA 2023 Quadruped Robot Challenge using a reinforcement learning scheme. After that, I have kept exploring reinforcement learning both for Sassa and Solo-12 to get more experience in this rising field for legged robot locomotion.
        - title: PhD Student
          company: Laboratory of Analysis and Architecture of Systems
          company_url: https://www.laas.fr/public/en/gepetto
          company_logo: org-gc
          location: Toulouse, France
          date_start: '2019-09-01'
          date_end: '2023-10-31'
          description: My PhD focused on model-based walking architecture for the quadruped robot Solo-12 and centered on a centroidal model predictive controller followed by an instantaneous whole-body inverse kinematics. After the implementation of a whole control architecture based on the state of the art, I proposed and tested possible improvements. I also collaborated with several team members in their respective research, including reinforcement learning, 3D footstep planning, simultaneous localisation and mapping.
        - title: Master Thesis
          company: Learning Algorithms and Systems Laboratory
          company_url: https://www.epfl.ch/labs/lasa/
          company_logo: org-gc
          location: Lausanne, Switzerland
          date_start: '2019-02-01'
          date_end: '2019-07-31'
          description: This master thesis involved the development of an algorithm to detect and avoid obstacles with a Ridgeback robotic platform. I had to implement the whole control scheme from low-level data retrieval with sensors to high-level data processing to build a map of the environment, which was successfully deployed on real hardware using ROS with real time performances.
        - title: Master Project
          company: Laboratory of Movement Analysis and Measurement
          company_url: https://www.epfl.ch/labs/lmam/
          company_logo: org-gc
          location: Lausanne, Switzerland
          date_start: '2018-10-01'
          date_end: '2019-01-01'
          description: This semester project was focused on the analysis of data from inertia measurement units that had been worn by meerkats in order to detect behavioural patterns such as feeding, foraging, grooming or looking out for predators. I used data-processing tool to spot and classify these activities in an automated way to remove the need for tedious hand-labeling. 
        - title: Internship
          company: Biorobotics Laboratory
          company_url: https://www.epfl.ch/labs/biorob/
          company_logo: org-gc
          location: Lausanne, Switzerland
          date_start: '2017-05-01'
          date_end: '2017-08-15'
          description: During this summer internship I was tasked with developing a set of experiments to highlight the potential of Roombots robots. I demonstrated their capabilities to build adaptive and self-organizing furniture as well as how they could assist elderly people. These experiments later served as proofs of concept for the Roombot project report.
        - title: Internship
          company: INRIA-IRISA Laboratory
          company_url: https://team.inria.fr/hybrid/
          company_logo: org-gc
          location: Rennes, France
          date_start: '2016-05-01'
          date_end: '2016-07-15'
          description: This internship was focused on the use of a passive haptic device to provide contact feedback to users in virtual environments. I designed several use cases to test its limits and assess its performances.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Education & Qualifications # 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2023-10-31'
          date_start: '2019-09-01'
          description: |2+
            * Locomotion control of a lightweight quadruped robot
            * Under the supervision of Philippe Souères and Thomas Flayols
            * Issued by the University Toulouse 3 Paul Sabatier
            * Defended October 17, 2022.
          organization: LAAS-CNRS, Gepetto team, France
          organization_url: https://www.laas.fr/public/en/gepetto
          title: 'PhD thesis'
          url: ''
        - certificate_url: ''
          date_end: '2019-07-31'
          date_start: '2018-09-01'
          description: |2+
            * Engineering of Complex Systems, Research track.
            * Academic exchange at Ecole Polytechnique Fédérale de Lausanne, Switzerland.
          organization: École Normale Supérieure de Rennes, France
          organization_url: https://international.ens-rennes.fr/
          title: 'Master of Science'
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2018-06-01'
          description: |2+
            * Industrial Engineering Sciences, electrical specialization
            * External exam, rank: 1st
          organization: French Ministry of Higher Education and Research
          organization_url: https://en.wikipedia.org/wiki/Agr%C3%A9gation
          title: 'Agrégation'
          url: ''
        - certificate_url: ''
          date_end: '2018-05-30'
          date_start: '2016-09-01'
          description: |2+
            * Engineering of Complex Systems, Teaching track.
          organization: École Normale Supérieure de Rennes, France
          organization_url: https://international.ens-rennes.fr/
          title: 'Master of Science'
          url: ''
        - certificate_url: ''
          date_end: '2016-06-30'
          date_start: '2013-09-01'
          description: |2+
            * Electronics and Telecommunications
            * Mechanics and Engineering Sciences
          organization: École Normale Supérieure de Rennes, France
          organization_url: https://international.ens-rennes.fr/
          title: 'Bachelors of Science'
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
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
