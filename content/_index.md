---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Moore Lab
      image:
        filename: lab-photo.jpg
      text: |
        <br>

        The **Translational Neuroimmunology Lab** at Memorial University of Newfoundland investigates how immune dysregulation drives blood-brain barrier breakdown and neurodegeneration, with a focus on multiple sclerosis biomarker discovery.

        <br>
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
        {{% cta cta_link="./research/" cta_text="Our research →" %}}

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

  - block: collection
    content:
      title: Latest Publications
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