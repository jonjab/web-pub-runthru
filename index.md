---
layout: home
title: Building Websites in Github 
---

## Description
This website was created to practice for a Carpentry workshop at the UCSB Library.

{{site.description}}

{% assign lead = site.team_members | where:"role", "project lead" | first
 %}
The project is led by {{ lead.name }}.
[See our full team](about#team)

[About this website](about)

[Read our lab diary](diary)

Have any questions? [Let us know!](mailto:{{ site.email }})


