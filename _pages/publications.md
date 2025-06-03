---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<style>
/* HTML/CSS pseudo-element after main body to add background image*/
body::before {
  content: "";
  background: url('../assets/img/cover_phd_impressionist_upscaled_brighter.png');
  background-size:cover;
  background-repeat:no-repeat;
  opacity: 0.4;
  background-position: 50% 0;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  z-index: -1;
}
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
