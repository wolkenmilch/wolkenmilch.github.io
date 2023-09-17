## Projects

{% for project in site.data.projects %}
  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  
  {{ project.description }}

  **Organisation**:  *{{ project.organisation }}*

  **Tools**: *{{ project.tools }}*

{% endfor %}

## Articles

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>