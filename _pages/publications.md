---
layout: page
permalink: /publications/
title: Research
description: Working papers, publications, work in progress, and other research.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Working Papers</h2>
{% bibliography --query @unpublished %}

<h2>Publications</h2>
{% bibliography --query @article %}

<h2>Work in Progress</h2>
{% bibliography --query @misc %}

<h2>Other Research</h2>
{% bibliography --query @techreport %}

</div>
