---
leyout: default
title: I downvoted because...
byline: all of these reasons...
---
## All the reasons
Here's the current list of all pages, sorted by community!  Not finding something you want? [See below to learn how to get it!](#call-to-action)

{% for cat in site.category-list %}
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

## Special thanks
Special thanks to [mrenaud and his answer here](https://stackoverflow.com/a/17913214/1228) for making this page possible.  