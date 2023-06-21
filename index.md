---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

<div class="profile_pic">
<img src="{{site.author.picture}}">
</div>

<div class="profile_pic_cap">
{%- include social.html -%}
</div>

{{ site.short-bio }}.

[More about TEF-Health](https://news.ki.se/major-eu-funding-for-development-of-ai-in-healthcare)

## Areas of interest

{% for item in site.areas-of-interest %}
* {{ item }}
{% endfor %}
