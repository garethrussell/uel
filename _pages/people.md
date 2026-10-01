---
title: "People"
layout: gridlay
sitemap: false
permalink: /people/
---

<div class="jumbotron">

{% comment %} 1. Convert the keyed dictionary into a flat array of values {% endcomment %}
{% assign members_array = "" | split: "" %}
{% for member in site.data.team_members %}
  {% assign members_array = members_array | push: member[1] %}
{% endfor %}

{% comment %} 2. Sort the array based on YAML key 'last name') {% endcomment %}
{% assign sorted_members = members_array | sort: "lastname" %}

{% comment %} 3. Loop through your newly ordered array to render them {% endcomment %}
{% for member in sorted_members %}

<div class="row">
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%">
</div>
<div class="col-sm-8 col-xs-12">
<h4>{{ member.lastname }}</h4>
<i>{{ member.degree }}</i><br>
{{ member.info }}<br>
{% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
{% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-2x"></i></a> {% endif %}
{% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
{% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %}
</div>
</div>

{% endfor %}

</div>
