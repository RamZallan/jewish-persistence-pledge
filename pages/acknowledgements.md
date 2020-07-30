---
layout: page
title: Acknowledgements
meta_description: |
  This sets the meta description in the head of the page. You can watch the 
  output in the browser or in the generated file _site/about.html.
permalink: /acknowledgements
section: acknowledgements
intro_paragraph: |
  This pledge was made possible by the people and organizations listed below.
---

{% for credit in site.acknowledgements %}
### [{{ credit.name }}]({{credit.link}})
{{ credit.description }}
{% endfor %}
