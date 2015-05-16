---
layout: page
title: Hackathons
permalink: /projects/hackathons/
---

Hackathons
====

<div>
      {% for post in site.categories.hackathons %}
          <div class="image-container row-large">
            <a href="{{ post.url }}" class="darken bot-left">
                <img src="{{ site.baseurl }}{{ post.thumbnail }}">
            </a>
            <h4 class="caption-title">{{ post.title }}</h4>
            <p>{{ post.desc }}</p>
          </div>
      {%endfor%}
</div>


More content is on it's way! Check back here for my projects from YHack 2014 and UofT Hacks 2015.
