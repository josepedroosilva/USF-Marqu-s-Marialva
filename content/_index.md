---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Sobre
        Nós
      image:
        filename: welcome2.jpg
      text: |
        <br>
        
        Somos uma equipa constituída por Médicos de Família, Enfermeiros, Secretários Clínicos, Assistente Operacional, Internos de Especialidade de Medicina Geral e Familiar, alunos de Medicina e Enfermagem, motivados para o servir melhor.

  - block: collection
    content:
      title: Notícias
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
          filename: coders2.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        
    design:
      columns: '1'
---