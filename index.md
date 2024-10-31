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
{% raw %}{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}{% endraw %}
