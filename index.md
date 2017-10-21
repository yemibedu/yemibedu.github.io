---
layout: default
title: Yemi Bedu
---
<html>
<body>
<h1>Yemi Bedu</h1>
<h2>Software Development</h2>

- HTML, CSS, Javascript
-  F#, F#, VB.Net
- Ruby, Scheme, Python
- C
<h2>
Information
</h2>
<div>
{% for post in site.posts %}
<br />
<h2>
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
</h2>
<blockquote>
<p>
{{ post.subtitle }} 
<!-- <time datetime="{{ post.date | date: '%Y-%m-%d' }}">({{ post.date | date: "%-d %B %Y" }})</time> -->
</p>
</blockquote>
{% endfor %}
</div>
</p>
</body>
</html>
