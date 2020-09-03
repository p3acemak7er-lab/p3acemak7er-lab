---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---
>>> from markdown import Markdown
>>> from fontawesome_markdown import FontAwesomeExtension

>>> markdown = Markdown(extensions=[FontAwesomeExtension()]
>>> markdown.convert('i ♥ :fa-coffee:')
<p>i ♥ <i class="fa fa-coffee"></i></p>
<head>
<link rel="stylesheet" type="text/css" href="header.css">
<script src="https://kit.fontawesome.com/c6be4965ce.js" crossorigin="anonymous"></script>

</head>

# bold_coding
<p>
    Please work
</p>

