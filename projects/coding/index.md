---
layout: page
title: Engineering design
permalink: /projects/coding/
---

Coding
======

<div>
      {% for post in site.categories.coding %}
          <div class="image-container row-large">
            <a href="{{ post.url }}" class="darken bot-left">
                <img src="{{ site.baseurl }}{{ post.thumbnail }}">
            </a>
            <h4 class="caption-title">{{ post.title }}</h4>
            <p>{{ post.desc }}</p>
          </div>
      {%endfor%}
</div>
