---
layout: page
title: Home
id: home
permalink: /
---
<img src = "/assets/potted-plant.png" style = "float: right" alt="Pixelated Potted Plant"/>
# Welcome!

This is my [digital garden](https://maggieappleton.com/garden-history), a place to grow my ideas. <octo-thorpe>digitalgarden<octo-thorpe>


My latest project is my podcast [[podcast|Anti-Inflammatory Rhetoric]]. 

I'm playing with a Q&A format, so leave me a question below and I'll feature it on an episode! [[Q-and-A-format|Why the new format? 🌱]]

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdGyC52gBN4zHfnEq80XttGGzbLF-evJRdSWLcKMk_-ZhLilw/viewform?embedded=true" width="640" height="660" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

I also do a bit of writing, check out my recent notes below.

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

<p>
[[what-s-the-all-about|What's the 🌱 all about?]]
</p>

<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="eedumas" data-color="#fece53" data-emoji="☕"  data-font="Cookie" data-text="Buy me a cup" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#FFDD00" ></script>

![Mac Plus](/assets/mac.png)
