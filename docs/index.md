---
layout: default
title: Research and development
---
# Example Docs
Here is some example documentation added to the repo.

<ul>
{% for org in site.data.orgs %}
  <li>
    <a href="{{ org.url }}">
      {{ org.name }}
    </a>
  </li>
{% endfor %}
</ul>

