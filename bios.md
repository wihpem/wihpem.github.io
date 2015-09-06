---
layout: page
title: Member Biographies
permalink: /bios/
---

<div class="home">

  <h1 class="page-heading">Bios</h1>

  <ul class="bio-list">
    {% for bio in site.bios %}
      <li>

        <h2>
          <a class="bio-link" href="{{ bio.url | prepend: site.baseurl }}">{{ bio.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

</div>
