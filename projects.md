---
layout: page
title: Projetos
permalink: projects
---

<div>
  {% for post in site.posts %}
    <div class="py-1">
      <!-- <img class="object-scale-down h-8 w-8" src="{{site.baseurl}}/assets/projects/{{ post.title }}.svg"> -->
      <h3><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h3>
      <div class="text-sm text-gray-400">{{post.date | date: "%B %-d, %Y"}}</div>
    </div>
  {% endfor %}
</div>


