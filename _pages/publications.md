---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p class="page__lead">
  {{ site.publications.size }} peer-reviewed journal articles. <span class="pub__me">Qiu Z</span> highlighted; <sup>#</sup> denotes equal contribution.
  Full and up-to-date list on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.
</p>

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign groups = pubs | group_by_exp: "p", "p.date | date: '%Y'" %}
{% for g in groups %}
<section class="pub-year">
  <h2 class="pub-year__label">{{ g.name }}</h2>
  <ul class="pub-list">
    {% for post in g.items %}{% include pub-entry.html %}{% endfor %}
  </ul>
</section>
{% endfor %}
