---
title: Student Contributions
layout: home
nav_order: 1
---

## Industry Projects for Python

This site documents student and learner contributions to the _Industry Projects for Python_ course. These contributions represent real-world preparation for internships, open source collaboration, and professional software development.

---

## Contributors (Jan–Mar 2026)

{% assign people = site.data.contributors | sort: "nav_order" %}

<ul>
{% for p in people %}
  <li>
    <a href="{{ p.url | relative_url }}">{{ p.name }}</a>
    — {{ p.university }} ({{ p.program }})
    {% if p.github_url %} · <a href="{{ p.github_url }}">GitHub</a>{% endif %}
    {% if p.linkedin_url %} · <a href="{{ p.linkedin_url }}">LinkedIn</a>{% endif %}
  </li>
{% endfor %}
</ul>

---
