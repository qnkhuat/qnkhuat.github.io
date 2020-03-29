---
layout: page
permalink: /cat/
title: Categories
---


{% for category in site.categories %}
{% capture category_name %}{{ category | first }}{% endcapture %}
## {{ category_name | capitalize}}
{% for post in site.categories[category_name] %}
{{ post.date | date: "%b %-d, %Y" }} - [{{post.title}}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
{% endfor %}
