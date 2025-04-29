---
layout: page
title: Home
id: home
permalink: /
---

# Welcome!

<img src = "/assets/potted-plant.png" style = "float: right" alt="Potted Plant"/>
This is my [digital garden](https://maggieappleton.com/garden-history), a place to grow my ideas.

My latest project is my podcast [[podcast|Anti-Inflammatory Rhetoric]] check it out, and if you'd like you can [[feedback|leave some feedback here.]]

I also do a bit of writing, check out my recent notes below.
<p>
[[what-s-the-all-about|What's the 🌱 all about?]]
</p>

<section class="recent-notes">
  <h2>Recent Notes</h2>
  <ul>
    {% for note in site.notes limit:4 %}
      <li>
        <a href="{{ note.url | relative_url }}">{{ note.title }}</a>
        <span class="note-date">{{ note.date | date: "%B %d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
</section>

![Mac Plus](/assets/mac.png)
