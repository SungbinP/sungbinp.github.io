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
  .jmp .abstract.hidden { display: block !important; }
  .jmp a.abstract.btn { display: none; }
  .jmp h2.bibliography { display: none; }
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

