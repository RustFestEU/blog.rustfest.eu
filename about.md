---
layout: blue_page
permalink: /about/
title: About
---

<section markdown="1">

## About Us

</section>

<section markdown="1">
## Team

<ul class="team">
  {% for member in site.data.team %}
    <li><div class="info">
      <h4>{{member.name}}</h4>
      <p>{{member.desc}}</p>
      <ul class="links">
        {% for link in member.links %}
          <li>{% include icons/{{link.icon}}.svg %} <a href="{{link.link}}" target="_blank">{{link.title}}</a></li>
        {% endfor %}
      </ul>
    </div>
    <img src="/assets/team/{{member.thumbnailUrl}}" /></li>
  {% endfor %}
</ul>

</section>
