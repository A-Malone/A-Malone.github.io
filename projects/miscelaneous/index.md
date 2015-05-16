---
layout: page
title: Engineering design
permalink: /projects/misc/
---

Miscellaneous
====

<div>
      {% for post in site.categories.miscelaneous %}
          <div class="image-container row-large">
            <a href="{{ post.url }}" class="darken bot-left">
                <img src="{{ site.baseurl }}{{ post.thumbnail }}">
            </a>
            <h4 class="caption-title">{{ post.title }}</h4>
            <p>{{ post.desc }}</p>
          </div>
      {%endfor%}
</div>

Content is on it's way! Check back for my blacksmithing work!
