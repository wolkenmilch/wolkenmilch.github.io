### Projects - a Journey through my Creations

---

{% for project in site.data.projects %}

  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>

  <div style='text-align: left;'>
    <img class='responsive-img' src='/market-wave-dynamics/Screenshot-WebModel.png' style='max-width: 30%;float: left; margin-right: 10px;'>
  </div>

  {{ project.excerpt }}
  <a href="{{ project.link }}">Learn More</a>

{% endfor %}

---
---

### Blog - Exploring Ideas and Insights

---

{% for post in site.posts %}

  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  {{ post.excerpt }}
  <a href="{{ post.url }}">Read More</a>

{% endfor %}