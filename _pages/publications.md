---
layout: page
permalink: /publications/
title: research
description: 
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->
<style>
  .jmp .abstract.hidden { max-height: none !important; overflow: visible !important; border: none !important; font-size: 1rem; }
  .jmp .abstract.hidden p { margin: 8px 0 0 0; }
  .jmp a.abstract.btn,
  .jmp h2.bibliography,
  .jmp .author,
  .jmp .periodical { display: none; }
</style>
<div class="publications jmp">
<strong><font size="+2">Job Market Paper</font></strong>

{% bibliography --file jobmarket %}
</div>

<hr style="height:3px;border-width:1;color:gray;background-color:gray">

<div class="publications">
<strong><font size="+2">Peer-Reviewed Publications</font></strong>

{% bibliography --file papers %}

<hr style="height:3px;border-width:1;color:gray;background-color:gray">

<strong><font size="+2">Working Papers</font></strong>

{% bibliography --file workingpapers %}

<hr style="height:3px;border-width:1;color:gray;background-color:gray">

<strong><font size="+2">Selected Work-in-Progress</font></strong>
</div>

