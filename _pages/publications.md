---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 5
---
<!-- _pages/publications.md -->
<div class="publications">

<p>For a listing of citations and other publication-related metrics, please see my <a href="https://scholar.google.com/citations?user=Pi012CQAAAAJ">Google Scholar</a> page.</p>

<h3>Books and Book Chapters</h3><br/>
{% bibliography  -f {{ site.scholar.bibliography }} --query @book %}

<h3>Journal Papers</h3><br/>
{% bibliography  -f {{ site.scholar.bibliography }} --query @article %}

<h3>Conference and Workshop Papers</h3><br/>
{% bibliography  -f {{ site.scholar.bibliography }} --query @inproceedings %}

<h3>Other Papers</h3><br/>
{% bibliography  -f {{ site.scholar.bibliography }} --query @phdthesis %}
{% bibliography  -f {{ site.scholar.bibliography }} --query @mastersthesis %}


</div>
