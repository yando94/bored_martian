---
layout: default
---

# Welcome!
Welcome to my website! Here is where I put my ideas, interests and experience
to be shown to the world. I hope you find something useful!

---

## Recent Posts
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>

---

## History
- 2022-05-17 - Created a GitHub Pages page. It's pretty empty but plans are
being made to fill it with content. First, I need to learn about [Jekyll](https://jekyllrb.com).

