---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: 
    username: admin
  id: about
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Publications
  design:
    columns: "2"
    view: card
  id: publications  
- block: collection
  content:
    filters:
      #featured_only: true
      folders:
      - papers
    count: 0  
    title: Working Papers
  design:
    columns: "2"
    view: card
    show_more_link: false
  id: featured
#- block: collection
#  content:
#    filters:
#      exclude_featured: true
#      folders:
#      - publication
#    text: |-
#      {{% callout note %}}
#      Quickly discover relevant content by [filtering publications](./publication/).
#      {{% /callout %}}
#    title: Recent Publications
#  design:
#    columns: "2"
#    view: citation
- block: contact
  content:
    address:
      city: Minneapolis
      country: United States
      country_code: US
      postcode: "55455"
      region: MN
      street: 1925 Fourth Street South
    #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: barre843@umn.edu
    #form:
    #  formspree:
    #    id: null
    #  netlify:
    #    captcha: false
    #  provider: netlify
    #office_hours:
    #- Monday 10:00 to 13:00
    #- Wednesday 09:00 to 10:00
    # phone: (+1) 202-352-6462
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
