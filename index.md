---
layout: page
title: "Hugues Chabot"
tagline: "Null Dereference"
---
{% include JB/setup %}

{% for post in site.posts limit:5 %}

### [{{ post.title}}]({{ post.url }})

{{ post.content | strip_html | truncatewords:48 }}
**[Read more.]({{ BASE_PATH }}{{ post.url }})**

**{{ post.date | date: "%B %e, %Y" }}** | [{{ post.category }}]({{ BASE_PATH }}{{ site.JB.categories_path }}#{{ post.category }}-ref)

{% endfor %}
