---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Journal Articles</h2>
{% bibliography -q @*[category=journal] %}

<div style="margin-top: 2rem;"></div>
<h2>Communication & Outreach</h2>
{% bibliography -q @*[category=outreach] %}

<div style="margin-top: 2rem;"></div>
<h2>Dissertations</h2>
{% bibliography -q @*[category=dissertation] %}

</div>
