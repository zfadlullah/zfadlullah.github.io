---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->
<!-- This file should be placed in the _pages directory of your al-folio site -->

<div class="publications">

<!-- Al-folio will automatically generate publication lists from your BibTeX file -->
<!-- The publications.bib file should be placed in _bibliography/ directory -->

<!-- You can use Jekyll-Scholar to filter and display publications by category -->

## Journal Articles

{% bibliography --query @article %}

---

## Conference Papers

{% bibliography --query @inproceedings %}

---

## Book Chapters

{% bibliography --query @incollection %}

</div>
