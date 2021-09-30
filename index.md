---
layout: default
---
<h1>সকল পাতা</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="https://tahmid02016.github.io/simplify/{{ post.urlname }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
