---
layout: single
permalink: /board/
sidebar:
  nav: "info"
---

<ul>
  {% for author in site.data.authors %}
    {% if author[1].board == "true"%}
      <li>
        {% if author[1].avatar %}
          <div class="author__avatar">
            {% if author[1].avatar contains "://" %}
              <img src="{{ author[1].avatar }}" alt="{{ author[1].name }}" itemprop="image">
            {% else %}
              <img src="{{ author[1].avatar | absolute_url }}" class="author__avatar" alt="{{ author[1].name }}" itemprop="image">
            {% endif %}
          </div>
        {% endif %}
        <div class="author__content">
          <h3 class="author__name" itemprop="name">{{ author[1].name }}</h3>
          {% if author[1].bio %}
            <p class="author__bio" itemprop="description">
              {{ author[1].bio }}
            </p>
          {% endif %}
        </div>
      </li>
    {% endif %}
  {% endfor %}
</ul>
