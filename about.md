---
layout: blue_page
permalink: /about/
title: About
---

RustConf is Europe’s first Rust-dedicated conference. The one day, single track event will take place in Berlin.

We care about diversity and accessibility at this conference.

<section>
  <h2>Team</h2>
  <ul class="team">
    {% for member in site.data.team %}
      <li>
        <img src="/assets/team/{{member.thumbnailUrl}}" />
        <div class="info">
          <span class="name">{{member.name}}</span>
          <ul class="links">
            {% for link in member.links %}
              <li><a href="{{link.link}}" target="_blank" title="{{link.title}}">{% include icons/{{link.icon}}.svg %}</a></li>
            {% endfor %}
          </ul>
        </div>
      </li>
    {% endfor %}
  </ul>
</section>
