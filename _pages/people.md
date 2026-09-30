---
title: "People"
layout: gridlay
sitemap: false
permalink: /people/
---

### PhD Students

{% for member in site.data.team_members %}

<div class="jumbotron">
  <div class="row">
    <div class="col-md-3">
      <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%"/>
    </div>
    <div class="col-md-9">
      <h4>{{ member.name }}</h4>
      <i>{{ member.info }}<br></i>
      {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-2x"></i></a> {% endif %}
      {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
      {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %}
      {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-2x"></i></a> {% endif %}
      {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %}
      {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
    </div>
  </div>
</div>

{% endfor %}
