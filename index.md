---
layout: single
author_profile: true
---

I'm Hrishav — a data and tech professional who spent six months teaching science in one of the most remote corners of Nepal.

Getting there took six days of trekking through mountain trails to a village with no phone, no internet, no radio, no television. That experience shaped how I think about hard problems: clearly, patiently, and with the person on the other end of it firmly in mind.

I completed my M.S. in Computer Science at the University of Toledo, where I worked as a Graduate Research Assistant on cybersecurity for smart grid infrastructure — publishing four IEEE papers on Zero Trust Architecture and Advanced Metering Infrastructure along the way. Currently I work as a Technical Support Engineer at Vepo Solutions.

Outside of work: ⚽ football, 🎸 guitar, 🥾 trekking.

---

<h3>Now</h3>

<!-- UPDATE this section whenever your situation changes — job, location, what you're learning or reading -->
- **Technical Support Engineer I** at Vepo Solutions
- Writing occasionally — see below

---

<h3>Recent Writing</h3>

{% if site.posts.size > 0 %}
<ul class="recent-posts">
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="timeline-date">{{ post.date | date: "%B %d, %Y" }}</span>
    {% if post.excerpt %}<p class="recent-post-excerpt">{{ post.excerpt | strip_html | truncatewords: 25 }}</p>{% endif %}
  </li>
{% endfor %}
</ul>
<p><a href="/blog/">All posts →</a></p>
{% else %}
<p>Nothing published yet — but something is in the works.</p>
{% endif %}
