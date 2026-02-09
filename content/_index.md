---
# Leave the homepage title empty to use the site title
title: "Shaw Lab"
subtitle: "Genetic and transcriptomic basis of parasite virulence and persistence"
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Shaw
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        We study the genetic and transcriptomic basis of virulence and persistence in the apicomplexan parasite *Cryptosporidium*. Using forward and reverse genetics, genome engineering, and host–parasite interaction studies, we aim to dsicover the origins of phenotypic differences across *Cryptosporidium* strains.
        
        **Interested in joining?** We’re recruiting motivated students and postdoctoral fellows via the Contact page.
  
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
