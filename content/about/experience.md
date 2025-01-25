---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: R&D Director
    company: VoxelDance
    company_url: https://voxeldance.com/
    company_logo: org-gc
    location: Shanghai
    date_start: '2019-04-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Mesh Boolean
        * Mesh Offset
        * Mesh thicken
        * Mesh Repair
        * Mesh 2D Nesting
        * Mesh 2.5D Nesting
        * Mesh 3D Nesting
        * Implicit modeling
        * Dental related algorithms


  - title: Algorithm Engineer
    company: UnionTech
    company_url: https://www.uniontech3d.com/
    company_logo: org-x
    location: Shanghai
    date_start: '2016-04-01'
    date_end: '2019-03-31'
    description: Wrote algorithms related to triangular meshes.

design:
  columns: '1'
---
