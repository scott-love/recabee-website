---
# Leave the homepage title empty to use the site title
title: RECABEE
date: 2024-09-17
type: landing

sections:
  - block: hero
    content:
      title: |
        À propos de RECABEE
      image:
        filename: recabee2.png
      text: |
        <br>
        
        Le Réseau Cognition Animal et Bien-être en Élevage regroupe des chercheurs, ingénieurs, techniciens et étudiants des départements [PHASE](https://www.inrae.fr/departements/phase) et [GA](https://www.inrae.fr/departements/ga) d’[INRAE](https://www.inrae.fr/) qui s'intéressent à la cognition animale, au bien-être et à leurs interrelations. Les membres du réseau travaillent dans une quinzaine de laboratoires de recherche répartis dans toute la France. Ils mènent des recherches sur une diversité d'animaux d'élevage, notamment les ovins, caprins, bovins, équins, porc, truites, volailles, lapins et insectes. Les principales attentes des membres du réseau sont de : 1) réfléchir aux liens entre cognition et bien-être animal ; 2) discuter des concepts et des méthodes de recherche et ; 3) mieux connaître les collègues qui mènent des recherches dans ces domaines.
  - block: collection
    content:
      title: Nos Derniers Événements
      subtitle: réunions en ligne et en présentiel
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
      title: À vos agenda
      subtitle: 'Webinaires, formations et conférences à venir'
      text: ''
      date_format: January 2, 2006
      items:
        - title: 3R - Rencontre Recherche Ruminants
          date_start: '2024-12-04'
          date_end: '2024-12-05'
          description: |2-
            *Congrès (Paris)*  
            3R 2024 - 27e édition Congrès international francophone  
          organization:
          organization_url:
          url: https://journees3r.fr/
        - title: PCI Webinar Series
          date_start: '2024-12-05'
          date_end: ''
          description: |2-
            *Webinaire • 16h-17h15 (en ligne)*  
            How much is too much? Estimating APCs and questioning sustainability  
          organization: 
          organization_url: 
          url: https://peercommunityin.org/pci-webinar-series/
        - title: IDELE
          date_start: '2024-12-09'
          date_end: ''
          description: |2-
            *Webinaire • 17h-18h (en ligne)*  
            La maîtrise durable des boiteries en bovins laitiers (2/2)  
          organization: 
          organization_url: 
          url: https://idele.fr/detail-evenement/la-maitrise-durable-des-boiteries-en-bovins-laitiers-2
        - title: Centre pour la Communication Scientifique Directe
          date_start: '2024-12-12'
          date_end: ''
          description: |2-
            *Webinaire • 14h-15h30 (en ligne)*  
            Logiciels et codes sources en science ouverte: du pratique à l'opérationnel
          organization: 
          organization_url: 
          url: https://www.ccsd.cnrs.fr/parlons-science-ouverte/
        - title: Responsible Research (UK)
          date_start: '2024-12-18'
          date_end: ''
          description: |2-
            *Webinaire • 15h-16h (en ligne)*  
            Guide to open research practices for animal research
          organization: 
          organization_url: 
          url: https://register.gotowebinar.com/register/5640597345748054109?source=Website
        - title: TARCforce3R (Allemagne)
          date_end: ''
          date_start: '2024-12-19'
          description: |2-
             *Webinaire • 14h -16h (en ligne)*  
             Why is our pain management failing?
          #organization: 
          #organization_url: 
          url: https://www.unimedizin-mainz.de/tarc-force-3r/veranstaltungen.html
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
      title: Publications
      subtitle: par les membres de RECABEE
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
        {{% cta cta_link="./people/" cta_text="Rencontrer le Réseau →" %}}
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
