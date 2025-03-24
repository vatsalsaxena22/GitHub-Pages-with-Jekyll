# GitHub Pages with Jekyll

GitHub Pages supports Jekyll, a static site generator that lets you create a professional multi-page website with Markdown.

## Steps for Making Complete Website with Markdown (without HTML)

 {% for post in site.posts %}
 - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
 {% endfor %}
