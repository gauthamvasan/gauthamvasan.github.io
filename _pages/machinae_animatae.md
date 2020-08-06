---
layout:     default
title:      Machinae Animatae
permalink:  /machinae_animatae/
---

# Machinae Animatae
 I've first came across the phrase _Machinae Animatae (i.e., Devices Animated)_  while reading Milan Kundera's masterpiece - "The Unbearable Lightness of Being". It's stuck with me ever since.   



<div class="row">
    <div class="col-xs-12">
        <ul class="entries">
            {% for post in site.posts %}
                <li>
                    <span class="title"><a href="{{ post.url }}">{{ post.title }}</a></span>
                    <span class="date">{{ post.date | date: "%d %B %Y" }}</span>
                </li>
            {% endfor %}
        </ul>
    </div>
</div>