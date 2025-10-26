---
title: "Publications"
permalink: /publications/
layout: single
author_profile: true
---

## Publications

{% for pub in site.data.publications %}
- **{{ pub.authors }}**  
  *{{ pub.title }}*  
  _{{ pub.venue }}_  
  {% if pub.url %}[🔗 Link]({{ pub.url }}){% endif %}
{% endfor %}
