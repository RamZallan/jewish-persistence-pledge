---
layout: page
title: Acknowledgements
meta_description: |
    Acknowledgements - Jewish Persistence Pledge
permalink: /acknowledgements
section: acknowledgements
intro_paragraph: |
  This pledge was made possible by the people and organizations listed below.
---

{% for credit in site.acknowledgements %}
### [{{ credit.name }}]({{credit.link}}){:target="_blank"}
{{ credit.description }}
{% endfor %}
