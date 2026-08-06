---
layout: default
title: Home
language: en
permalink: /en/home/
translation: home
---

<section class="hero">

<h2>
Understanding human behaviour through psychology
</h2>

<p>
Exploring psychological research, behaviour change,
and the science behind everyday decisions.
</p>

</section>


<div class="card">

<h2>Featured Article</h2>

<h3>
Why Is Change So Difficult?
</h3>

<p>
Why do we struggle to change habits, even when we know what is best for us?
This article explores motivation, automatic behaviour, and the psychology
behind lasting change.
</p>

<a class="button" href="#">
Read article
</a>

</div>



<h2>Latest Articles</h2>


{% for post in site.posts limit:3 %}

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



<div class="card">

<h2>Explore Topics</h2>

<p>
🧠 Behaviour Change
<br>
💬 Social Psychology
<br>
🌱 Sustainability Psychology
<br>
🔬 Research Explained
</p>

</div>
