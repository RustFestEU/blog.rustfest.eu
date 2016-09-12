---
layout: default
permalink: /sponsoring/
title: Sponsoring
---

<div class="popout sponsors">
  <section>
    <h1>Sponsors</h1>
    <hr />
    <p>
      RustConf wouldn't be possible without the generous support of these fine folks:
    </p>
      <ul class="primary">
        {% for sponsor in site.data.sponsors %}
          {% if sponsor.group == 'sponsor' %}
            <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.logoName}}" /></a></li>
            {% if sponsor.desc %}
            <li><p>{{sponsor.desc}}</p></li>
            {% endif %}
          {% endif %}
        {% endfor %}
      </ul>
  </section>

  <section>
    <h2>Partners</h2>
    <hr />
      <ul>
        {% for sponsor in site.data.sponsors %}
          {% if sponsor.group == 'partner' %}
            <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.logoName}}" /></a></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>


  <section>
    <h2>Venues</h2>
    <hr />
      <ul>
        {% for sponsor in site.data.sponsors %}
          {% if sponsor.group == 'venue' %}
            <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.logoName}}" /></a></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>

  <section>
    <h2>Media Partner</h2>
    <hr />
      <ul>
        {% for sponsor in site.data.sponsors %}
          {% if sponsor.group == 'media' %}
            <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.logoName}}" /></a></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>
</div>


<section class="whitewithwheel">
  <h2>Interested in Sponsoring?</h2>
  <p>Learn more about <a href="/assets/downloads/rustfest_2016_sponsorship.pdf">RustFest's Sponsorship Packages here</a>.
  </p>
  <br />
  <p>
    <a class="button" href="mailto:sponsors@rustfest.eu">
      Get in touch now
    </a>
  </p>
</section>
