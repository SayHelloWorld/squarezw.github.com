---
layout: page
title: Hello World!
tagline: square
---
{% include JB/setup %}

like objc & ruby

mail: <square.zhao.wei@gmail.com>

[Github](https://github.com/squarezw)

[Weibo](http://weibo.com/squarezw)

[LinkedIn](http://www.linkedin.com/in/squarezw)

----

<!-- ## Sample Posts -->

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

