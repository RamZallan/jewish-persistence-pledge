---
layout: page
title: Resources
meta_description: |
    Resources - Jewish Persistence Pledge
permalink: /resources
section: resources
intro_paragraph: |
    Here are some helpful resources to learn more
---

{% for item in site.resources %}
### [{{ item.title }}]({{item.link}}){:target="_blank"}
{{ item.description }}
{% endfor %}
