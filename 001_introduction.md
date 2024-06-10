---
layout: default
title: The Source
number: 001
---

# The Source

World War One Poster

{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %} 
