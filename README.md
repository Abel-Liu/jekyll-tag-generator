# Instructions

Generate page for every tag in your posts.

# Useage

* Put `generate_tag_page.rb` into your `_plugins` directory.
* Put `tagpage.html` into your `_layouts` directory.


Use the tag pages like this:

```html
---
layout: default
---
<h1>Tags</h1>
{% for tag in site.tags %}
    <a href="/tag/{{ tag[0] }}">{{ tag[0] }}</a>
{% endfor %}
```

# Mark

You can find a sample at [my blog](www.abelliu.com).