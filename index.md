# GitHub Pages with Jekyll

GitHub Pages supports Jekyll, a static site generator that lets you create a professional multi-page website with Markdown.

## Follow these steps:

 {% for post in site.posts %}
 - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
 {% endfor %}
