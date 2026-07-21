---
layout: page
permalink: /publications/
title: Research
description: Click "Abs" to read the abstract, or "PDF" for a current draft where available.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h4>Working Papers</h4>
{% bibliography --query @unpublished --group_by none %}

<h4>Publications</h4>
{% bibliography --query @article --group_by none %}

<h4>Work in Progress</h4>
{% bibliography --query @misc --group_by none %}

<h4>Reports</h4>
{% bibliography --query @techreport --group_by none %}

</div>
