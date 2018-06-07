---
title: "Civic X"
layout: post
tags: car civicx
permalink: /civicx
---

<ul style="">
    {% for post in site.posts %}
        {% if post.categories contains "civicx" %}
            <p>lsls</p>
        {% endif %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
            {{ post.excerpt }}
        </li>
    {% endfor %}
</ul>
---