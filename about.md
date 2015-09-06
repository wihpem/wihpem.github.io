---
layout: page
title: About
permalink: /about/
---

<div class="home">

  <h1 class="page-heading">About W(i)HPEM</h1>

  <ul class="a-list">
    {% for a in site.about %}
      <li>

        <h2>
          <a class="a-link" href="{{ a.url | prepend: site.baseurl }}">{{ a.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

</div>
