---
layout: homepage
permalink: /cv/
---

### Academic Experience
<ul style="list-style: none; padding-left: 0;">
{% for link in site.data.cv.academic %}
<li>
<div class="pub-row" style="display: flex; align-items: flex-start; margin-bottom: 0em;">
    
  <div style="min-width: 140px; padding-left: 0px; font-weight: bold; color: #337ab7; flex-shrink: 0;">
      {{ link.date }}
  </div>
    
  <!-- Right column: Talk details -->
  <div class="col-sm-9" style="padding-left: 20px; padding-right: 15px;">
    <div class="title" style="font-weight: bold; font-size: 13pt">{{ link.title }}</div>
    <div class="location" style="margin-bottom: 0px;">{{ link.location }}</div>
    </div>
  </div>
</li>
{% endfor %}
</ul>

### Education
<ul style="list-style: none; padding-left: 0;">
{% for link in site.data.cv.education %}
<li>
<div class="pub-row" style="display: flex; align-items: flex-start; margin-bottom: 0em;">
    
  <div style="min-width: 140px; padding-left: 0px; font-weight: bold; color: #337ab7; flex-shrink: 0;">
      {{ link.date }}
  </div>
    
  <!-- Right column: Talk details -->
  <div class="col-sm-9" style="padding-left: 20px; padding-right: 15px;">
    <div class="title" style="font-weight: bold; font-size: 13pt">{{ link.title }}</div>
    <div class="location" style="margin-bottom: 0px;">{{ link.location }}</div>
    </div>
  </div>
</li>
{% endfor %}
</ul>


### Honours and Awards (selected)
<ul style="list-style: none; padding-left: 0;">
{% for link in site.data.cv.awards %}
<li>
<div class="pub-row" style="display: flex; align-items: flex-start; margin-bottom: 0em;">
    
  <div style="min-width: 80px; padding-left: 0px; font-weight: bold; color: #337ab7; flex-shrink: 0;">
      {{ link.date }}
  </div>
    
  <!-- Right column: Talk details -->
  <div class="col-sm-9" style="padding-left: 20px; padding-right: 15px;">
    <div class="title" style="font-weight: bold; font-size: 13pt">{{ link.title }}</div>
    <div class="location" style="margin-bottom: 0px;">{{ link.location }}</div>
    </div>
  </div>
</li>
{% endfor %}
</ul>




