---
layout: default
---

You've found __I/O__, the technical "nerd blog" from the Puget Sound Regional Council in Seattle Washington. PSRC also has a general-interest blog on our main website, at http://www.psrc.org

<div class="posts">
  {% for post in site.posts %}
    <article class="post">    
      
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.content | truncatewords:40}}
      </div>
      
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>

