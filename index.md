---
layout: layout.html
---

<h1> Hello </h1>

<p>It works.</p>

<ul>
{%- for post in collections.post reversed -%}
  <li>
    <a href="{{post.url}}">
      {{ post.data.title }}
    </a>
  </li>
{%- endfor -%}
</ul>

<a href="/posts/2020-07-04-first-post">First post</a>

 
<a href="/posts/2020-07-03-diary">Diary post</a>

