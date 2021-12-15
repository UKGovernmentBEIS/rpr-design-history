---
layout: collection
title: Interaction and visual design
description: Interaction and visual design decisions on BEIS RPR
pagination:
  data: collections.interaction-design
  reverse: true
  size: 50
permalink: "interaction-design/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
related:
  items:
  - text: RPR beta prototype
    href: https://rpr-prototype.herokuapp.com/
---