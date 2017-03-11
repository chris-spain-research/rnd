---
layout: default
title: Research and development
---
# Example Docs
Here is some example documentation added to the repo.


## Organizations

{% for org in site.data.mockorgs %}
- [{{ org.name }}]({ org.url })
{% endfor %}

