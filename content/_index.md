---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-20
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
        
        Le Réseau Cognition Animal et Bien-être en Élevage regroupe des chercheurs, ingénieurs, techniciens et étudiants des départements [PHASE](https://www.inrae.fr/departements/phase) et [GA](https://www.inrae.fr/departements/ga) d’[INRAE](https://www.inrae.fr/) qui s'intéressent à la cognition animale, au bien-être et à leurs interrelations. Les membres du réseau travaillent dans une quinzaine de laboratoires de recherche répartis dans toute la France. Ils mènent des recherches sur une diversité d'animaux d'élevage, notamment les ovins, caprins, bovins, équins, porc, truites, volailles et insectes. Les principales attentes des membres du réseau sont de : 1) réfléchir aux liens entre cognition et bien-être animal ; 2) discuter des concepts et des méthodes de recherche et ; 3) mieux connaître les collègues qui mènent des recherches dans ces domaines.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
