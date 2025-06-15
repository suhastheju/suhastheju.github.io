---
layout: homepage
permalink: /blog/
---

<div style="display: flex; justify-content: space-between; align-items: center;">
  <span><strong> <h2> Hello World ... </h2> </strong></span>
  <span style="font-style: italic;">June 15, 2025</span>
</div>


{% capture included_content %}
{% include_relative _blog/hello-world-02-july-2025.md %}
{% endcapture %}
{{ included_content | markdownify }}
