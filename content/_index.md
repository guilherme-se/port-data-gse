---
# Leave the homepage title empty to use the site title
title: GSE
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Sobre
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Tecnologias 
      items:
        - name: Java
          icon: java
          icon_pack: fab
        - name: Python
          icon: python
          icon_pack: fab
        - name: JavaScript
          icon: js
          icon_pack: fab
        - name: Wordpress
          icon: wordpress
          icon_pack: fab
        - name: MySQL
          icon: mysql
          icon_pack: custom
        - name: PostgreSQL
          icon: postgree
          icon_pack: custom   
  - block: experience
    id: experience
    content:
      title: Experiências
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Estagio de Ti
          company: Predictus
          company_url: ''
          company_logo: ''
          location: Florianopolis
          date_start: '2022-04-01'
          date_end: '2022-08-01'
          description: |2-
              Competências: Java, Jenkins, BitBucket, Linux

              * Empresa focada em WebScrapy (raspagem de dados)
              * Verificava, Realizava ajustes e criação de testes unitarios em Bots
              
        - title: Auxiliar de escritório/Ti
          company: ConCrédito Consignados
          company_url: ''
          company_logo: ''
          location: Osório
          date_start: '2021-11-01'
          date_end: '2022-04-30'
          description: |2-
              Competências: WordPress · HTML · CSS · JavaScript · PHP

              * Administrava o site principal da empresa e do site de suporte para vendedores.
              * Resolvia problemas que ocorriam nas propostas de clientes com os bancos de acordo com sua politica.
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificados'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://cursos.alura.com.br/degree/certificate/416d5a88-141b-4a47-a61c-fd8f4bcaba11
          date_end: ''
          date_start: '2023-07-03'
          description: ''
          organization: alura_
          organization_url: https://www.alura.com.br
          title: Formação SQL com MySQL Server da Oracle
          url: ''
        - certificate_url: https://cursos.alura.com.br/degree/certificate/c9acc2f0-c67e-41f1-8e6f-ce7bd358d72d
          date_end: ''
          date_start: '2023-05-17'
          description: ''
          organization: alura_
          organization_url: https://www.alura.com.br
          title: Formação Java e Spring Boot
          url: https://cursos.alura.com.br/degree/certificate/c9acc2f0-c67e-41f1-8e6f-ce7bd358d72d

        - certificate_url: https://www.dio.me/certificate/38F3DE1A/share
          date_end: ''
          date_start: '2023-02-20'
          description: ''
          organization: dio
          organization_url: https://www.alura.com.br
          title: 'Formação Java Developer'
          url: https://www.dio.me/certificate/38F3DE1A/share

        - certificate_url: https://www.freecodecamp.org/certification/guilherme-dos-santos-de-espindula/scientific-computing-with-python-v7
          date_end: ''
          date_start: '2022-12-13'
          description: ''
          organization: freecodecamp
          organization_url: https://www.freecodecamp.org
          title: 'Scientific Computing with Python'
          url: https://www.freecodecamp.org/certification/guilherme-dos-santos-de-espindula/scientific-computing-with-python-v7
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projetos
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
        - name: Todos
          tag: '*'
        - name: WebScrapy
          tag: WebScrapy
        - name: Outros
          tag: Outros
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contato
      subtitle:
      text: |-
        Entre em Contato para Trabalharmos Juntos ☕
      # Contact (add or remove contact options as necessary)
      # email: test@example.org
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
    design:
      columns: '2'
---

