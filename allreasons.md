---
title: I downvoted because...
byline: all of these reasons...
---
## Categories
{% for cat in site.categories %}
### {{ cat }}
<ul>
  {% for page in site.pages %}
      {% for pc in page.categories %}
        {% if pc == cat %}
          <li><a href="{{ page.url }}">{{ page.title }}</a></li>
        {% endif %}   <!-- cat-match-p -->
      {% endfor %}  <!-- page-category -->
  {% endfor %}  <!-- page -->
</ul>
{% endfor %}  <!-- cat -->