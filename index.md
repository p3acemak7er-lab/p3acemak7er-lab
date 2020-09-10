---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults]
layout: post
header: A Developer's Story
title: Home Base
include{{ }}


---
<html>
<head>


</head>
<style type="text/css">
.h1 {
    font-family: Fantasy, Chalkduster, serif;
    color: slateblue;
}
</style>

<h1>
{{ page.header }}
</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</html>

