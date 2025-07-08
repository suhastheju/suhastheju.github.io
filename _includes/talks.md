<div class="publications">
<ol class="bibliography">


<h2 id="talks" style="margin: -30px 0px 15px;">Talks</h2>

{% for link in site.data.talks.talks %}
<li>
<div class="pub-row" style="display: flex; align-items: flex-start; margin-bottom: 0em;">
    
  <!-- Left column: Date -->
  <div style="min-width: 100px; padding-left: 40px; font-weight: bold; color: #337ab7; flex-shrink: 0;">
      {{ link.date }}
  </div>
    
  <!-- Right column: Talk details -->
  <div class="col-sm-9" style="padding-left: 20px; padding-right: 15px;">
    <div class="title">{{ link.title }}</div>
    <div class="location" style="margin-bottom: 0px;">{{ link.location }}</div>
    </div>
  </div>
</li>
<div style="margin-top: -20px;"></div>
{% endfor %}
</ol>
</div>

