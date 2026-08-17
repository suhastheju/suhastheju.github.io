---
layout: homepage
permalink: /blog/
---

<div style="display: flex; justify-content: space-between; align-items: center;">
  <span><strong> <h2> Why human-in-the-loop is not enough for high-stakes decision making</h2> </strong></span>
  <span style="font-style: italic;">June 02, 2026</span>
</div>

{% capture included_content %}
{% include_relative _blog/human-in-the-loop-jun-2026.md %}
{% endcapture %}

{{ included_content | markdownify }}

<div style="display: flex; justify-content: space-between; align-items: center;">
  <span><strong> <h2> Attention is all you have</h2> </strong></span>
  <span style="font-style: italic;">January 25, 2026</span>
</div>

{% capture included_content %}
{% include_relative _blog/instant-messaging-25-jan-2026.md %}
{% endcapture %}

<div style="margin-bottom: -0.5em;"></div>

{{ included_content | markdownify }}

<div style="display: flex; justify-content: space-between; align-items: center; margin-top:1.5em">
  <span><strong> <h2> Hello World ... </h2> </strong></span>
  <span style="font-style: italic;">June 15, 2025</span>
</div>

{% capture included_content %}
{% include_relative _blog/hello-world-02-july-2025.md %}
{% endcapture %}

{{ included_content | markdownify }}
