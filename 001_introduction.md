---
layout: default
title: Introduction
number: 001
---

# Introduction

MinDoc Manual: A Minimal Computing Template for Publishing Digital Documentary Editions of Primary Sources

Liza Senatrova, John Randolph, Caroline Kness

{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %} 
