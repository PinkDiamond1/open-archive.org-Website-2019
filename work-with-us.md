---
layout: page
title: Work with Us
description:
permalink:
---
<div class="row">
  <div class="6u 12u$(medium)">
    {% for post in site.posts %}
      {% if post.tags contains 'job' %}
        {% if post.hidden %}
          {% continue %}
        {% endif %}
        <div>
          <b><a href="{{ site.baseurl }}{{ post.url }}" style="color: #00B4A6">{{ post.title }}</a></b>
          <br>
          <span style="font-style: italic; font-size: 14px;">{{ post.date | date_to_string }}</span>
          <p style="margin-top: 6px">{{ post.description }}</p>
        </div>
      {% endif %}
    {% endfor %}
	</div>
</div>
