---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Research test

<div class="jumbotron">
{% for project in site.data.projects %}
<b>{{ project.name }}</b>

{{ project.desc }}
{% endfor %}

</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Research</h4>

Our research group defines structural ecology as a subset of spatial ecology that focuses on the dynamic interaction between individual organisms and the structure and pattern of their surroundings. We ask: What do they perceive? If they can move, how do they navigate? Find each other? Avoid risk?

We ask these questions because much of spatial ecology, such as biogeography and metapopulation theory, contains rather implausible assumptions about how individuals disperse in their environment. This makes predictions based on these theories suspect, which is disturbing given that they are the foundation for a lot of conservation activity.

In practice, our lab studies animal movements in relation to their environment, and how these translate into broader population and species-level dynamics.

<div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/wordcloud.png" width="60%"/>
</center>
</div>
</div>
<br/>

</div>
</div>

