---
layout: default
---
<h1>সকল পাতা</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.urlname }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
