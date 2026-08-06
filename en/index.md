---
layout: default
title: Home
language: en
permalink: /en/home/
translation: home
---

<section class="hero">

<h1>
Understanding human behaviour
through psychological science
</h1>

<p>
Exploring psychology, behaviour change, and the science behind
the choices we make every day.
</p>

</section>


<div class="card">

<h2>Hello, I'm Sophia</h2>

<p>
I am a psychology communicator with a Master's degree in Behaviour Change Psychology.
I am passionate about making psychological research accessible and showing how
scientific insights can be applied to everyday life.
</p>

<p>
Through this website, I explore topics such as behaviour change, mental health,
motivation, and the psychological factors that influence human behaviour.
</p>

<a class="button" href="{{ '/en/about/' | relative_url }}">
Learn more about me →
</a>

</div>



<h2>Featured Articles</h2>


<div class="card">

<h3>
Why Is Change So Difficult?
</h3>

<p>
Understanding habits, motivation, and the psychological processes
behind lasting behaviour change.
</p>

<a href="#">
Read article →
</a>

</div>


<div class="card">

<h3>
The Psychology of Everyday Decisions
</h3>

<p>
Exploring how our thoughts, emotions, and environment shape the choices we make.
</p>

<a href="#">
Read article →
</a>

</div>



<h2>Explore Topics</h2>


<div class="card">

<p>
🧠 <strong>Behaviour Change</strong>
<br>
How people develop, maintain, and change behaviours.
</p>

<p>
💬 <strong>Everyday Psychology</strong>
<br>
Psychological concepts explained through everyday examples.
</p>

<p>
🌱 <strong>Sustainability Psychology</strong>
<br>
Understanding why people do (or do not) make sustainable choices.
</p>

<p>
🔬 <strong>Research Explained</strong>
<br>
Making psychological research understandable and accessible.
</p>

</div>



<div class="card">

<h2>Latest Articles</h2>

{% for post in site.posts limit:3 %}

<h3>
<a href="{{ post.url }}">
{{ post.title }}
</a>
</h3>

<p>
{{ post.excerpt }}
</p>

{% endfor %}

</div>
