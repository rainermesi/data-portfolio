---
layout: default
---

# Data Portfolio

Welcome to my technical blog where I showcase projects and document my journey in data engineering and analysis. Here you'll find:
- Data Engineering Projects
- Data Analysis Case Studies
- Technical Tutorials
- Visualizations
- Learning Resources

## Latest Posts
{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
