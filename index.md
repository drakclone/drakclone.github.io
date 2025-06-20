---
title: Home
layout: default
---

# Tokyo night theme
Cool theme which I just named Tokyo night for fun

## About

Welcome to the Tokyo Night Jekyll Theme! This theme is inspired by the Tokyo Night VSCode color scheme.

## Features

- Dark mode support
- Responsive design

## Blog Posts

{% for post in site.posts %}
  <article>
    <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
    <p>{{ post.date | date: "%B %d, %Y" }}</p>
    <span>{{ post.excerpt }}</span>
  </article>
{% endfor %}


## Contact

Feel free to reach out via [GitHub](https://github.com/IamSTEINI).