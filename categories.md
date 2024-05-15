---
title: Categories
layout: categories
excerpt: "Category index"
aside: true
---

<footer>
  <nav>
    <ul>
      {% for item in site.navigation_footer %}
        <li>
          <a href="{{ item.url }}">
            {% if item.icon %}
              <img src="{{ item.icon }}" alt="{{ item.title }}" class="icon">
            {% else %}
              {{ item.title }}
            {% endif %}
          </a>
        </li>
      {% endfor %}
    </ul>
  </nav>
</footer>
