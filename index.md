## Projects

{% for project in site.data.projects %}

  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  {{ project.description }}
  **Organisation**:  *{{ project.organisation }}*
  **Tools**: *{{ project.tools }}*

{% endfor %}

## Posts

{% for post in site.posts %}

  {{ post.excerpt }}
  <a href="{{ post.url }}">Read More</a>

{% endfor %}