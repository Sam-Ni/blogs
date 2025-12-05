---
title: Welcome to my website
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  ## Hello world
---

There isn't much going on here yet, but watch this space.

# Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> 
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>
