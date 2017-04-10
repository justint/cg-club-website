---
layout: page

title: Events
subtitle: "Past and future plans for the club"
#cover_image: blog-cover.jpg

#excerpt: "Incorporated provides a great typography, responsive design, author details, semantic markup and more."

---


### Upcoming events:

<br>

{% for post in site.posts %}
{% unless post.draft or post.categories contains 'archives' %}
  <section class="index">
      <!-- {% if post.author.image %}<img src="/images/{{ post.author.image }}" class="avatar">{% endif %}-->
      <div>
          <a name="{{ post.id }}"></a><h2 class="title"><a href="{{ post.url }}" rel="prefetch">{{ post.title }}</a></h2>
          <p>{{ post.excerpt }}</p>
          <div class="meta">
              Written By <address>{{ post.author.name }}</address> &mdash;
              <time pubdate datetime="{{ post.date | date: "%Y-%d-%B" }}" title="{{ post.date | date: "%B %d, %Y" }}">{{ post.date | date: "%B %d, %Y" }}</time>
          </div>
      </div>
      <hr>
  </section>
  {% endunless %}
  {% endfor %}

### Calendar:

<div class="full">
<iframe src="https://calendar.google.com/calendar/embed?src=sjsu.edu_8dlke4itf4ohb82g0mpu8vao3c%40group.calendar.google.com&ctz=America/Los_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe></div>
