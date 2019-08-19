---
layout: page
title: Arts
permalink: /arts/
---
My hobby is making art. As a big fan of anime, I grew up amazed by the colorful imagery that artists produced.
Therefore, I want to produce my own artworks especially animation.
There are links of different forms of artworks that I made. 

<ul>
    {% for art in site.categories.art %}
    <li>
        <a href="{{art.url}}">{{ art.title }}</a>
    </li>
    {% endfor %}
</ul>
