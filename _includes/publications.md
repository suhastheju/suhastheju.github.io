
<div class="publications">
<ol class="bibliography">


<h2 id="publications" style="margin: -30px 0px 15px;">Working papers</h2>

{% for link in site.data.publications.preprint %}

{% if link.type == "preprint" %}
<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">
        <a href="{{ link.pdf }}" target="_blank" rel="noopener">{{ link.title}}</a>
      </div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em></div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.poster %} 
        <a href="{{ link.poster }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Poster</a>
      {% endif %}
      {% if link.slides %} 
        <a href="{{ link.slides }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Slides</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
    {% if link.workshop %}
      <div class="workshop">††  {{ link.workshop }}</div>
    {% endif %}
    {% if link.alphabeta %}
      <div class="alphabeta">** Authors listed in alphabetical order</div>
    {% endif %}
    {% if link.notes %}
      <div class="notes"> <i style ="color:#e74d3c">{{ link.notes }}</i></div>
    {% endif %}
  </div>
</div>
</li>
<div style="margin-top: 1.5em;"></div>
{% endif %}
{% endfor %}


<h2 id="publications" style="margin: 0px 0px 15px;">Publications</h2>
{% for link in site.data.publications.published %}
{% if link.type == "proceedings" or link.type == "journal" %}
<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
     <div class="title"><a href="{{ link.pdf }}" target="_blank" rel="noopener">{{ link.title }}</a> </div>
     <div class="author">{{ link.authors }}</div>
     <div class="periodical"><em>{{ link.conference }}</em> </div>
     <div style="display: flex; gap: 1em;">
         {% if link.accp-rate %}
           <div class="rate">Accp. rate: {{ link.accp-rate }} ,</div>
         {% endif %}
         {% if link.conf-rating %}
           <div class="conf">Conf. rating: {{ link.conf-rating }}</div>
         {% endif %}
         {% if link.impact-factor %}
           <div class="journal">Impact factor: {{ link.impact-factor }}</div>
         {% endif %}
    </div>
    <div class="links">
      {% if link.pdf %} 
        <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
        <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
        <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.blogpost %}
        <a href="{{ link.blogpost }}" class="btn btn-sm z-depth-0" role="button" target="_blank"
style="font-size:12px;">Blog Post</a>
      {% endif %}
      {% if link.poster %} 
        <a href="{{ link.poster }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Poster</a>
      {% endif %}
      {% if link.slides %} 
        <a href="{{ link.slides }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Slides</a>
      {% endif %}
      {% if link.bibtex %} 
        <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
        {{ link.others }}
      {% endif %}
    </div>
    {% if link.workshop %}
      <div class="workshop">††  {{ link.workshop }}</div>
    {% endif %}
    {% if link.alphabeta %}
      <div class="alphabeta">** Authors listed in alphabetical order</div>
    {% endif %}
    {% if link.notes %}
      <div class="notes"> <i style ="color:#e74d3c">{{ link.notes }}</i></div>
    {% endif %}
  </div>
</div>
</li>
<div style="margin-top: 1.5em;"></div>
{% endif %}
{% endfor %}




</ol>
</div>

