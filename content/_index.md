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
        
        The [INRAE](https://www.inrae.fr/) Farm Animal Cognition and Welfare network consists of the researchers, engineers, technicians and students of the [Departments PHASE](https://www.inrae.fr/departements/phase) and [GA](https://www.inrae.fr/departements/ga) who are interested in animal cognition, welfare and their interrelationship. Members of the network come from about 14 different research laboratories from all over France. They conduct research on a variety of farm animals including sheep, goats, cattle, horses, pigs, trout, poultry and insects. The main expectations of the network’s members are: 1) to think about the link between cognition and welfare; 2) to discuss the concepts and methods of both cognition and welfare research and; 3) to get to know better colleagues conducting research in these areas.
  
  - block: collection
    content:
      title: Les derniers événements
      subtitle:
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
    content:
      title: Contact RECABEE
      email: recabee@inrae.fr
      align: centre
      # Automatically link email and phone or display as text?
      autolink: true
---
