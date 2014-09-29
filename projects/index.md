---
layout: page
title: Projects
permalink: /projects/
---

Projects
========

Engineering Design
----
<div>
      <div class="image-container row-small">
        <a href="{{site.baseurl}}/projects/design/trident" class="darken bot-left">
            <img height="200" src="{{ site.baseurl }}/assets/thumbnails/trident.png">
        </a>
        <h4 class="caption-title">Trident Lock</h4>
        <p>An integrated bike lock to combat theft</p>            
      </div>

      <div class="image-container row-small">
        <a href="{{site.baseurl}}/projects/design/bmec2014" class="darken bot-left">
            <img height="200" src="{{ site.baseurl }}/assets/thumbnails/bmec.jpg">
        </a>
        <h4 class="caption-title">Biomedical Engineering Competition 2014</h4>
        <p>A simple, low-cost, robot to perform ELISA tests</p>
      </div>
      <div class="image-container row-small">
        <a href="{{site.baseurl}}/projects/design/trussdesign" class="darken bot-left">
            <img height="200" src="{{ site.baseurl }}/assets/thumbnails/trussdesign.jpg">
        </a>
        <h4 class="caption-title">CIV102 Truss Bridge Design</h4>
        <p>A pedestrian bridge designed for cost and safety</p>
      </div>
</div>

Coding
-----

<div>    
      <div class="image-container row-small">
        <a href="{{site.baseurl}}/projects/coding/psibot" class="darken bot-left">
            <img height="200" src="{{ site.baseurl }}/assets/thumbnails/psibot.bmp">
        </a>  
        <h4 class="caption-title">Psibot</h4>
        <p>A networked 2.5D platformer made as a class project</p>
      </div>
      <div class="image-container row-small">
        <a href="{{site.baseurl}}/projects/coding/genetic" class="darken bot-left">
            <img height="200" src="{{ site.baseurl }}/assets/thumbnails/optimizer.png">
        </a>  
        <h4 class="caption-title">Genetic Algorithms</h4>
        <p>A simple network optimizer using genetic algorithms created as a learning exercise</p>
      </div>
</div>


Hackathons
----
Content is on it's way! Check back here for my projects from YHack 2013 and Hack the North 2014.


Miscellaneous
----
Content is on it's way! Check back for my blacksmithing work!



<!-- {% for category in site.categories %}
  <div class="category-list">
  <h1>
  <a name="{{ category | first }}">{{ category | first }}</a>
  </h1>
    <ul class="post-list">
    {% for posts in category %}
      {% for post in posts limit 4%}
        <li>
            <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
            <h2>
              <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
            </h2>
            <p>{{ post.excerpt }}</p>
            <a href="{{ post.url }}">Read more...</a>
        </li>
      {% endfor %}
    {% endfor %}
    </ul>
  </div>
{% endfor %} -->