---
layout: page
title: "Talks"
permalink: /talks/
---

<ul class="posts">
    {% for post in site.categories.talks %}
        <li>
            <a class="reserved" href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
