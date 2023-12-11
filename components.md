---
title: Components
layout: basic
---

# Collapsible containers

{% assign cards = site.data.collapsible_data['collapsible_data'] %}
{% include collapsible.html cards=cards %}

# Cards

[Design system cards reference](https://design-system.w3.org/components/cards.html)

## Simple cards

[Simple card with icon](https://design-system.w3.org/components/cards.html#simple-card-with-icon)

{% include card_simple.html title="Web Design and Applications" content="The standards for building and Rendering Web pages, including HTML, CSS, SVG, Ajax, and other technologies for Web Applications (\"WebApps\"). Includes information on how to make pages accessible (WCAG), to internationalize them, and make them work on mobile devices." %}

## Cards with image

[Simple card with image](https://design-system.w3.org/components/cards.html#simple-card-with-image)

{% include card_image.html title="W3C starts web payments standards work" content="New working group launched to make payments easier and more secure." imageurl="https://design-system.w3.org/dist/assets/images/temp-developers-1520.jpg" imagealt="A Macbook screen with code" %}

## Block link cards

[Block link cards](https://design-system.w3.org/components/cards.html#block-link-cards)

{% include card_link.html url="https://www.w3.org/" title="W3C starts web payments standards work" content="New working group launched to make payments easier and more secure." imageurl="https://design-system.w3.org/dist/assets/images/temp-developers-1520.jpg" imagealt="A Macbook screen with code" %}
