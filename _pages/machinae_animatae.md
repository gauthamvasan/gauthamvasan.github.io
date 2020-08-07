---
layout:     default
title:      Machinae Animatae
permalink:  /machinae_animatae/
---

<br>

# Machinae Animatae

<center>
<img src="/img/WallE_starry_night.jpg">
</center>

<br>

Since the dawn of mankind, philosophers, scientists and poets alike have sought to understand one of the most enigmatic mysteries of our universe - the human mind. Inverting René Descartes’ famous axiom on mind-body dualism - “I think, therefore I am”, I study the mind based on the principle that our mind is a set of processes carried out by the brain. In this stance, our brain is a complex biological machine that gives rise to thoughts, feelings, memories, behavior and the creative powers that are a hallmark of human experience. My goal is not limited to understanding what intelligence is and how the brain functions, but how to build robots with human-like intelligence. 

This space should chronicle my efforts of I came across the phrase _Machinae Animatae (i.e., Devices Animated)_  while reading Milan Kundera's masterpiece - "The Unbearable Lightness of Being". It's stuck with me ever since. Besides, the term nicely complements Eastern philosophies that posit we are animated anthropomorphic beings created from inanimate matter. The main purpose of this space is to distill my learning, scientific thoughts & reasoning and finally articulare them in a clear, concise manner.  


  

<br>

## Posts

<br>

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