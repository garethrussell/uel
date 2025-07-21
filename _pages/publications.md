---
title: "Departmental Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2020, 2021, 2022, 2023, 2024, 2025]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

### Refereed journal articles
<div class="jumbotron">
#### 2025
{% bibliography --query @*[year=2025] %}
</div>

<div class="jumbotron">
#### 2024
{% bibliography --query @*[year=2024] %}
</div>

<div class="jumbotron">
#### 2023
{% bibliography --query @*[year=2023] %}
</div>

<div class="jumbotron">
#### 2022
{% bibliography --query @*[year=2022] %}
</div>

<div class="jumbotron">
#### 2021
{% bibliography --query @*[year=2021] %}
</div>

<div class="jumbotron">
#### 2020
{% bibliography --query @*[year=2020] %}
</div>

<div class="jumbotron">
### Book chapters
{% bibliography --query @inbook %}
</div>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

