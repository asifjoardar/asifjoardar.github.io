---
layout: default
title: About
---

<!--
---
layout: default
title: Index
---
-->

<!--
<div class="posts">
  {% for post in paginator.posts %}
    {% if post.pinned %}
      <div class="post">
        <h1 class="post-title">
          <a href="{{ site.baseurl }}{{ post.url }}">
            {{ post.title }}
          </a>
        </h1>
        <div class="hr"></div>
        <span class="post-date">{{ post.date | date_to_long_string }}</span>
          {{ post.content }}
      </div>
      <hr>
    {% endif %}
  {% endfor %}
-->
<!--
  {% for post in paginator.posts %}
    {% unless post.pinned %}
      {% if post == site.posts.first %}
        <div class="lead alert">
          <i class="fas fa-exclamation-circle"></i> &nbsp; Newest Post
        </div>
      {% endif %}
      <div class="post">
        <h1 class="post-title">
          <a href="{{ site.baseurl }}{{ post.url }}">
            {{ post.title }}
          </a>
        </h1>
        <div class="hr"></div>
        <span class="post-date">{{ post.date | date_to_long_string }}</span>
          {{ post.content }}
      </div>
      {% if post != paginator.posts.last %}
        <hr>
      {% endif %}
    {% endunless %}
  {% endfor %}
</div>
-->
## Hi there! āšš¤
## peace be upon you š
I'm Asif, competitive programmer and undergraduate student of CSE and who loves to solve programming problems and participate online/offline programming competitions. Currently, i get familiar with web development and have a lot of interest in AI and ML.

If you want to reach out to me, then just email me at [asif170088@diit.edu.bd](https://asifjoardar.github.io/).


<!--
**asifjoardar/asifjoardar** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
<!--
<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}/page{{paginator.next_page}}"><i class="fas fa-arrow-left"></i> &nbsp; Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/">Newer &nbsp; <i class="fas fa-arrow-right"></i></a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/page{{paginator.previous_page}}">Newer &nbsp; <i class="fas fa-arrow-right"></i></a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
<div class="only-mobile alert">
  <a href="#" class="underline">Back to Top &nbsp; <i class="fa fa-arrow-circle-up"></i></a>
</div>
-->
