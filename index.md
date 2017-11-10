---
layout: page
title: Dessin D’enfant—a math sketchpad
---

A Math Sketchpad
============

**This blog is under construction**

a complete archive of <a href = "tp/past">past</a> posts are
available via links at the top of the page.

Recent Posts
------------

{% for post in site.posts limit:5 %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  <a class="comments" href="{{ post.url }}#disqus_thread">View Comments</a>
  </p>
  <p class="excerpt">{{ post.excerpt }}</p>
</div>
{% endfor %}

<p>
<a href="tp/past">Older Posts &rarr;</a>
</p>

<script type="text/javascript">
//<![CDATA[
(function() {
		var links = document.getElementsByTagName('a');
		var query = '?';
		for(var i = 0; i < links.length; i++) {
			if(links[i].href.indexOf('#disqus_thread') >= 0) {
				query += 'url' + i + '=' + encodeURIComponent(links[i].href) + '&';
			}
		}
		document.write('<script type="text/javascript" src="https://disqus.com/forums/markreid/get_num_replies.js' + query + '"></' + 'script>');
	})();
//]]>
</script>