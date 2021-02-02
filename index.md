---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# C++ advice
{% for post in site.cppadvice %}
  [{{ post.title }}]({{ post.url }})
{% endfor %}
