---
title: Geez O' Pete
subtitle: A curated repository of Michigan recipes
permalink: "/"
layout: page
home: true
---

## Recent recipes —
{%- import "list.njk" as list -%}
{{ list.details(collections.posts) }}
