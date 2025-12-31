---
layout: post
title:  "2019 New Orleans"
author: Minho
categories: [ Annual Meeting ]
image: assets/images/meeting/2019 New Orleans/47.avif
featured: true
---

<div class="image-gallery" style="display: flex; flex-direction: column; gap: 1.5rem; max-width: 100%; margin: 0 auto;">
    {% for i in (1..47) %}
    <div class="gallery-item" style="width: 100%;">
        <img src="{{ site.baseurl }}/assets/images/meeting/2019 New Orleans/{{ i }}.avif" 
             alt="2019 New Orleans Meeting Photo {{ i }}" 
             style="width: 100%; height: auto; display: block; border-radius: 2px; box-shadow: 0 1px 3px rgba(0,0,0,0.1);">
    </div>
    {% endfor %}
</div>
