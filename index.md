## Projects
a Journey through my Creations

{% for project in site.data.projects %}

  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  {{ project.description }}
  **Organisation**:  *{{ project.organisation }}*
  **Tools**: *{{ project.tools }}*

{% endfor %}

## Blog
Exploring Ideas and Insights

{% for post in site.posts %}

  {{ post.title }}
  
  {{ post.excerpt }}
  <a href="{{ post.url }}">Read More</a>

{% endfor %}