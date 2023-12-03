---
layout: page
title: Project Presentation
permalink: /Project Presentation/
nav_order: 4
---

# Project Presentation

<iframe width="800" height="450" src="https://www.youtube.com/embed/wsreQK2l0nU?si=H-3UKoL_mn87t8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<br>

<br>

# Presentation Slide Deck

{% for report in site.static_files %}

{% if report.path contains "KI-1-AI-Security-Presentation.pdf" %}

<object data="{{site.url}}{{site.baseurl}}{{report.path}}" width="800" height="450" type='application/pdf'/>
</object>

{% endif %}

{% endfor %}
