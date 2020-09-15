---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults]
layout: post
header: A Developer's Story
title: Home Base
---
<head>



<style type="text/css">
.h1 {
    font-family: Fantasy, Chalkduster, serif;
    color: slateblue;
}
</style>
</head>

<h1>
{{ page.header }}
</h1>
<h2>{{ site.data..docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

