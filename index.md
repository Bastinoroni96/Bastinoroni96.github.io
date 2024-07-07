---
layout: home
---

# Welcome to My Portfolio

Here are some of my projects:

{% for project in site.projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.title }}
    </a>
  </h2>
  <p>{{ project.description }}</p>
{% endfor %}