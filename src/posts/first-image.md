---
title: The first post, test image thing
subtitle: Included just for fun :)
description: My first post. Checking out the responsive image shortcode.
date: '2021-08-16'
tags:
  - blog
  - image
layout: layouts/post.njk
---
This is a test post. I need to see if the template's responsive image shortcode works.

{% imageMd "./src/assets/images/volvo.jpg", "Ink in water", "(min-width: 30em) 50vw, 100vw", "grid-column-center", "img-post", " " %}