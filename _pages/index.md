---
layout: page
title: Home
id: home
permalink: /
---
<img src = "/assets/potted-plant.png" style = "float: right" alt="Pixelated Potted Plant"/>
# Welcome!

This is my [digital garden](https://maggieappleton.com/garden-history), a place to grow my ideas.


My latest project is my podcast [[podcast|Anti-Inflammatory Rhetoric]]. 

I'm playing with a Q&A format, so leave me a question below and I'll speak to it on an episode!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdGyC52gBN4zHfnEq80XttGGzbLF-evJRdSWLcKMk_-ZhLilw/viewform?embedded=true" width="640" height="660" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

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
