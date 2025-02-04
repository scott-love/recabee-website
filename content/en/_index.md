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
        - title: Animal Welfare Slack Workspace - Applying Ethology
          date_end: ''
          date_start: '2025-01-13'
          description: |2-
            *Webinaire • 20h (en ligne)*  
            Factors affecting grazing and rumination behaviours of dairy cows in pasture-based systems
          #organization: 
          #organization_url: 
          url: https://gdoc.pub/doc/e/2PACX-1vTPSRp0QnGTS4wwnLUqswE-ExoCmbCMby9r-swhBqx9ZTNmBNeB33U4XqEDcmKEMdWnhetO_QAtDyuv
        - title: TARCforce3R (Allemagne)
          date_end: ''
          date_start: '2025-01-24'
          description: |2-
             *Webinaire • 14h -16h (en ligne)*  
             Animal Welfare Frontiers: Considering Insect Welfare in Farming and Research
          #organization: 
          #organization_url: 
          url: https://www.unimedizin-mainz.de/tarc-force-3r/veranstaltungen.html
        - title: Observatoire de Recherche sur la Condition Animale
          date_start: '2025-01-14'
          date_end: ''
          description: |2-
            *Webinaire • 18h (s'inscrire à la liste de diffusion pour avoir le lien)*  
            Comment la poule est-elle devenue un animal à aimer ?  
            l'ascension de l'animal dans la hiérarchie humanimale
          #organization: 
          #organization_url: 
          url: https://orcanimale.fr/liste-de-diffusion/#
        - title: Académie d'Agriculture de France
          date_start: '2025-01-23'
          date_end: ''
          description: |2-
            *Colloque • 9h- 14h (Paris & en ligne)*  
            Faire battre One Health au coeur de la France
          #organization: 
          #organization_url: 
          url: https://www.academie-agriculture.fr/actualites/academie/colloque/academie/faire-battre-one-health-au-coeur-de-la-france
        - title: INRAE RDV COMPET'ences.
          date_start: '2025-01-23'
          date_end: ''
          description: |2-
            *Webinaire • 13h30-15h (en ligne)*  
            Exploration des liens entre émotions et cognition chez les animaux de ferme   
            pour mieux comprendre le bien-être animal  
            (DL inscription: 21/01)
          organization: 
          organization_url: 
          url: https://nextcloud.inrae.fr/s/NKt5SkMgELndaZo
        - title: COST TEATIME Action |
          date_start: '2025-01-28'
          date_end: ''
          description: |2-
            *Webinaire • 12h- 14h (en ligne) *  
            The Art of Communicating Animal Research in the 21st Century - First Webinar
          #organization: 
          #organization_url: 
          url: https://www.cost-teatime.org/events/the-art-of-communicating-animal-research-in-the-21st-century-first-webinar/
        - title: Animal Welfare Slack Workspace - Applying Ethology
          date_start: '2025-02-03'
          date_end: ''
          description: |2-
            * Webinaire • 20h (en ligne)*  
            Impact of farrowing crate enrichment strategies on the welfare, behavior, and performance of sows, suckling piglets, and post-weaning piglets
          #organization: 
          #organization_url: 
          url: https://gdoc.pub/doc/e/2PACX-1vTPSRp0QnGTS4wwnLUqswE-ExoCmbCMby9r-swhBqx9ZTNmBNeB33U4XqEDcmKEMdWnhetO_QAtDyuv
        - title: TARCforce3R (Allemagne)
          date_end: ''
          date_start: '2025-02-14'
          description: |2-
             *Webinaire • 14h -16h (en ligne)*  
             Communicating animal research on social media
          #organization: 
          #organization_url: 
          url: https://www.unimedizin-mainz.de/tarc-force-3r/veranstaltungen.html
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
