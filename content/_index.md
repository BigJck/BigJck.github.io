---
title: ''
summary: ''
date: 2026-07-04
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research sits at the intersection of educational psychology and cognitive neuroscience. I am interested in how learners use prior knowledge during naturalistic learning, and how learning-related cognitive processes are reflected in behavioral performance and neural representations.

        Methodologically, I work with behavioral and neuroimaging approaches to study learning in educationally meaningful contexts. I am especially interested in how individual differences and event-level learning processes shape shared and distinct neural patterns across learners.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
---
