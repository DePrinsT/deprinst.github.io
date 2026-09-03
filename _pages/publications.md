---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<style>
/* Container holding your background and content */
body {
  position: relative;
  /* Ensures text contrasts beautifully against the background as opacity drops */
  background-color: var(--global-bg-color) !important; 
}

/* Pseudo-element strictly handling the background image */
body::before {
  content: "";
  position: fixed; /* Keeps the background full-screen and static while scrolling */
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  
  /* Point to your asset image path */
  background-image: url('../assets/img/cover_phd_impressionist_low_size_brighter.jpg'); 
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  
  /* Adjust your background transparency here (0.0 fully clear to 1.0 fully solid) */
  opacity: 0.2;
  
  /* Pushes the background layer completely behind the main portfolio content */
  z-index: -1;
}
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
