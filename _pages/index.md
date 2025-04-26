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

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 4 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

![Mac Plus](/assets/mac.png)
