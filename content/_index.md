---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: talks
    content:
      title: Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: publications
    content:
      title: Publications & Preprints
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: teaching
    content:
      title: Teaching
      text: Classes taught go here
      filters:
        folders:
          - event
    design: 
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: bssweeting@ua.edu
      address:
        street: 505 Hackberry Lane
        city: Tuscaloosa
        region: AL
        postcode: '35401'
        country: United States
        country_code: US
      directions: Gordon Palmer Hall 139
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
