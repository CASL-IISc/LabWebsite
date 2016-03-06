---
layout: page
title: Publications
---

***
<h3>Selected Recent Publications</h3>

{% for member in site.data.publications %}
* [{{  member.name }}]({{ member.link }}){:target="_blank"}<br>
<b>{{ member.authors }}</b><br> {{ member.conference }}
{% endfor %}

***

<h3>A Few Selected Older Publications</h3>

{% for member in site.data.publications_old %}
* [{{  member.name }}]({{ member.link }}){:target="_blank"}<br>
<b>{{ member.authors }}</b><br> {{ member.conference }}
{% endfor %}