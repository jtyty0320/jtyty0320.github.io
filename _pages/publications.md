---
layout: page
permalink: /publications/
title: Publications
description: "* corresponding author. For citation counts, see my <a href='https://scholar.google.com/citations?user=xOHG348AAAAJ&hl=en'>Google Scholar</a> profile."
nav: true
nav_order: 2
---

<link rel="stylesheet" href="{{ '/assets/style/custom.css' | relative_url }}">

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="cy-pub-sec">International Journals</h2>
{% bibliography --query @article %}

<h2 class="cy-pub-sec">International Conferences</h2>
{% bibliography --query @inproceedings %}

</div>
