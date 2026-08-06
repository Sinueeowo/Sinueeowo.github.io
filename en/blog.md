---
layout: default
title: Blog
language: en
---

<h1>Psychology Blog</h1>

<p>
Exploring psychological research, theories, and ideas about human behaviour.
</p>


<h2>Categories</h2>

<div class="card">

<h3>🧠 Behaviour Change</h3>

<p>
How habits form, why change is difficult, and what helps people create lasting changes.
</p>

</div>


<div class="card">

<h3>🌱 Sustainability Psychology</h3>

<p>
Understanding why people make sustainable choices — and why they sometimes don't.
</p>

</div>


<div class="card">

<h3>💬 Everyday Psychology</h3>

<p>
Psychological concepts explained through everyday examples.
</p>

</div>


<h2>Latest Posts</h2>

{% for post in site.posts %}

<div class="card">

<h3>
<a href="{{ post.url }}">
{{ post.title }}
</a>
</h3>

<p>
{{ post.excerpt }}
</p>

</div>

{% endfor %}
