---
layout: default
title: Introduction
number: 001
---
# MinDoc

**A Minimal Computing Template for Publishing Digital Documentary Editions of Primary Sources**

By Liza Senatorova, John Randolph, Caroline Kness 

{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'introduction'" | where_exp: "item", "item.media_type == 'image'" %}
{% include media.html pages=intro_images %}
