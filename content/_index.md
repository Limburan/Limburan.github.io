---
# Leave the homepage title empty to use the site title
title: Agata Staniewicz
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: R
  #        description: 90%
  #        icon: r-project
  #        icon_pack: fab
  #      - name: Statistics
  #        description: 100%
  #        icon: chart-line
  #        icon_pack: fas
  #      - name: Photography
  #        description: 10%
  #        icon: camera-retro
  #        icon_pack: fas
  - block: experience
    content:
      title: Research experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral researcher
          company: Adam Mickiewicz University
          company_url: 'http://behaecol.home.amu.edu.pl/'
          company_logo: amu
          location: Poznań, Poland
          date_start: '2021-02-14'
          date_end: ''
          description: Investigating interspecific competition in bird communities in boreal, temperate and tropical forests using passive acoustic monitoring and playback experiments.
        - title: PhD researcher
          company: University of Bristol
          company_url: 'https://bristol.ac.uk/biology/'
          company_logo: bristol
          location: Bristol, UK
          date_start: '2015-09-20'
          date_end: '2020-01-05'
          description: Established species-specific vocal repertoires and tested acoustic monitoring methods for crocodile populations in Southeast Asia and West Africa.
        - title: Field assistant
          company: ZSL Tsaobis Baboon Project
          company_url: 'http://tsaobisbaboonproject.org/'
          company_logo: tsaobis
          location: Tsaobis, Namibia
          date_start: '2014-04-01'
          date_end: '2014-11-01'
          description: Collected behavioural data and perfromed playback experiments on wild chacma baboons as part of a long-term project. 
        - title: MSc researcher
          company: University of Bristol
          company_url: 'https://bristol.ac.uk/biology/'
          company_logo: bristol
          location: Bristol, UK
          date_start: '2010-10-20'
          date_end: '2013-06-01'
          description: Investigated ecological niche partitioning between sympatric crocodilians in a threatened wetland in East Kalimantan.
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
        - name: Bioacoustics
          tag: Bioacoustics
        - name: Ecology
          tag: Ecology
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        [Filter](./publication/) publications.
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  #- block: accomplishments
  #  content:
  #    # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Featured'
  #    subtitle:
  #    # Date format: https://wowchemy.com/docs/customization/#date-format
  #    date_format: Jan 2006
  #    # Accomplishments.
  #    #   Add/remove as many `item` blocks below as you like.
  #    #   `title`, `organization`, and `date_start` are the required parameters.
  #    #   Leave other parameters empty if not required.
  #    #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #    items:
  #      - certificate_url: ''
  #        date_end: ''
  #        date_start: '2023-09-29'
  #        description: ''
  #        organization: New Scientist
  #        organization_url: ''
  #        title: We’ve just realised that a tiny West African crocodile can moo
  #        url: 'https://www.newscientist.com/article/2394829-weve-just-realised-that-a-tiny-west-african-crocodile-can-moo/'
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: In the media
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
  - block: markdown
    content:
      title: Fieldwork photos
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  #- block: collection
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

  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: agata.staniewicz[at]gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      #address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
        #- icon: twitter
        #  icon_pack: fab
        #  name: DM Me
        #  link: 'https://twitter.com/AgataStaniewicz'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
        #- icon: video
        #  icon_pack: fas
        #  name: Zoom Me
        #  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
