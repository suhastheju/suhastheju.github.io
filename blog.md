---
layout: homepage
permalink: /blog/
---

## Hello World ...


{% capture included_content %}
{% include_relative _blog/hello-world-02-july-2025.md %}
{% endcapture %}
{{ included_content | markdownify }}
