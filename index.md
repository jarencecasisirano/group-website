---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: home
---

# Building Websites in GitHub

## Description
{{ site.description }}
{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](about#team)

Have any questions about what we do? [We'd love to hear from you!](mailto:{{ site.email }})

## Blog Posts

{% include post_list.html %}
