---
layout: page
permalink: /publications/
title: publications
description: journal papers, conference papers & drafts, patents, and theses
nav: true
nav_order: 0
---
<!-- _pages/publications.md -->

## journal papers
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} %}
</div>

## conference papers & drafts
<div class="publications">
{% bibliography -f {{ site.scholar.confs }} %}
</div>

## patent
<div class="publications">
{% bibliography -f {{ site.scholar.patents }} %}
</div>

## phd thesis
<div class="publications">
{% bibliography -f {{ site.scholar.phd_thesis }} %}
</div>

## diploma thesis
<div class="publications">
{% bibliography -f {{ site.scholar.diploma_thesis }} %}
</div>