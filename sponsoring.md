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
      <ul>
        {% for sponsor in site.data.sponsors %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.logoName}}" /></a></li>
        {% endfor %}
      </ul>
  </section>

  <section style="text-align:center">
    <h2>Organised in partnership with</h2>
    <a title="view source by Mozilla" href="https://viewsourceconf.org/berlin-2016/"><img src="/assets/sponsors/viewsource.png" style="min-height: 220px; min-width: 220px; width: 30vw; height: 30vw; max-height: 30vw; max-width: 30vw;">
    </a>
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
