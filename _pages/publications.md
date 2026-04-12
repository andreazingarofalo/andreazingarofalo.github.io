---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Journal Articles</h2>
{% bibliography -q @*[category=journal] --group_by none %}

<div style="margin-top: 3rem;"></div>
<h2>Dissertations</h2>
{% bibliography -q @*[category=dissertation] --group_by none %}

<div style="margin-top: 3rem;"></div>
<h2>Outreach</h2>
{% bibliography -q @*[category=outreach] --group_by none %}

</div>
