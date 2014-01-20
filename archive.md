---
layout: default 
---
### Lastest posts

<div class="hfeed">
	{% for post in site.posts %}
	    <article class="hentry entry">
	    	<p>
	    	<a href="{{ base.url }}{{ post.url }}">{{ post.title }}</a></p>
	    </article>
	{% endfor %}
</div>