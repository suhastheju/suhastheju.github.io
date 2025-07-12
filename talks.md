---
layout: homepage
permalink: /talks/
---

## Talks

<ul style="list-style: none; padding-left: 0;">
{% for link in site.data.talks.talks %}
<li>
<div class="pub-row" style="display: flex; align-items: flex-start; margin-bottom: 5pt;">
    
  <!-- Left column: Date -->
  <div style="min-width: 80px; padding-left: 0px; font-weight: bold; color: #337ab7; flex-shrink: 0;">
      {{link.date}}
  </div>
    
  <!-- Right column: Talk details -->
  <div class="col-sm-9" style="padding-left: 20px; padding-right: 15px;">
    <div class="title">{{ link.title }}</div>
    <div class="location" style="margin-bottom: 0px;">{{ link.location }}</div>
    </div>
  </div>
</li>
{% endfor %}
</ul>

