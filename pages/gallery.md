---
layout: page
title: Drones
subtitle: Fotografía aérea
permalink: /gallery/
gallery_path: "assets/img/pexels"
excluded: true
position: 3
tags: [Page]
feature-img: "assets/img/header/drone.jpg"
---

This is a photo gallery made from the static files in the `assets/img/pexels` folder. 
I wanted to automatically create a simple gallery from a folder without having to create a markdown page as you would for the portfolio.


{% include gallery.html gallery_path=page.gallery_path %}
