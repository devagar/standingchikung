---
layout: default
title: writing 
---
## Writing

<div class="hfeed">
	{% for post in site.posts %}
	    <article class="hentry entry">
	    	<p>
	    	<a href="{{ base.url }}{{ post.url }}">{{ post.title }}</a>

	    	<time datetime="{{ post.date | xmlschema }}">{{ post.date | date: "- %B %d, %Y" }}</time>
	    	</p>
	    </article>
	{% endfor %}
</div>