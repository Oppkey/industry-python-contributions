---
title: Contributors
nav_order: 2
---

# Contributors (Jan–Mar 2026)

Student and learner contributions to the *Industry Projects for Python* course from January 2026 through March 2026.

{% assign people = site.contributors | sort: "nav_order" %}

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

## Helped Identify Curriculum Problems

[People who identified curriculum problems]({{ '/curriculum-feedback/' | relative_url }}) — feedback that uncovered issues in the course material.
