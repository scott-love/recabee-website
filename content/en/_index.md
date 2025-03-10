---
# Leave the homepage title empty to use the site title
title: RECABEE
date: 2024-09-17
type: landing

sections:
  - block: hero
    content:
      title: |
        About RECABEE
      image:
        filename: recabee2.png
      text: |
        <br>
        
        The [INRAE](https://www.inrae.fr/) Farm Animal Cognition and Welfare network consists of the researchers, engineers, technicians and students of the [Departments PHASE](https://www.inrae.fr/departements/phase) and [GA](https://www.inrae.fr/departements/ga) who are interested in animal cognition, welfare and their interrelationship. Members of the network come from about 14 different research laboratories from all over France. They conduct research on a variety of farm animals including sheep, goats, cattle, horses, pigs, trout, poultry, rabbits and insects. The main expectations of the network’s members are: 1) to think about the link between cognition and welfare; 2) to discuss the concepts and methods of both cognition and welfare research and; 3) to get to know better their colleagues conducting research in these areas.
  - block: collection
    content:
      title: Our Latest Events
      subtitle: online and in-person meetings
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '1'
  - block: accomplishments
    id: agenda
    content:
      title: This Months Agenda
      subtitle: 'Upcoming related webinars, educational courses and conferences'
      text: ''
      date_format: January 2, 2006
      items:
        #- title: 
        #  date_start: '2025-10-17'
        #  date_end: '2025-10-18'
        #  description: |2-
        #    * *  
        #  organization: 
        #  organization_url: 
        #  url:
        - title: TARCforce3R (Allemagne)
          date_end: ''
          date_start: '2025-03-14'
          description: |2-
             *Webinaire • 14h (en ligne)*  
             The goats who stare at scientists - towards a cognitive approach to human-animal interactions in farm animals
          #organization: 
          #organization_url: 
          url: https://www.unimedizin-mainz.de/tarc-force-3r/veranstaltungen.html
        - title: PCI Webinar Series
          date_start: '2025-03-20'
          date_end: ''
          description: |2-
            *Webinaire • 16h (en ligne)*  
            When Open Publishing Is Not Fair
        #  organization: 
        #  organization_url: 
          url: https://peercommunityin.org/pci-webinar-series/
        - title: FC3R
          date_start: '2025-03-13'
          date_end: ''
          description: |2-
            *Webinaire • 13h - 14h (en ligne)*  
            Raffiner l’administration de substances chez les rongeurs
        #  organization: 
        #  organization_url: 
          url: https://www.fc3r.com/webinaires/raffiner-administration-substances-chez-rongeurs-20.html
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      background:
        #color: "#ed6e6c" 
        gradient_start: '#f0c0bf'
        gradient_end: '#ed6e6c'
        # The gradient angle from 0-360 degrees
        gradient_angle: 90
  - block: collection
    content:
      title: Related publications
      subtitle: from RECABEE members
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: compact
      columns: '2'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the network →" %}}
    design:
      columns: '1'
      background:
        image: 
          filename: frontcows.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  - block: contact
    id: homecontact
    content:
      title: Contact RECABEE
      email: recabee@inrae.fr
      align: centre
      # Automatically link email and phone or display as text?
      autolink: true
---
