---
title: Test page
layout: basic
---

## Test

Hello World!

### subsection

{% assign cards = site.data.collapsible_data['posts'] %}
{% include collapsible.html cards=cards %}
