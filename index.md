{% for project in site.data.projects %}
  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  
  {{ project.description }}

  **Organisation**:  *{{ project.organisation }}*

  **Tools**: *{{ project.tools }}*

{% endfor %}
