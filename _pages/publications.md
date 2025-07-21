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

### Recent refereed journal articles (by year)
<div class="jumbotron">
#### 2025
{% bibliography --query @article[year=2025] %}
</div>

<div class="jumbotron">
#### 2024
{% bibliography --query @article[year=2024] %}
</div>

<div class="jumbotron">
#### 2023
{% bibliography --query @article[year=2023] %}
</div>

<div class="jumbotron">
#### 2022
{% bibliography --query @article[year=2022] %}
</div>

<div class="jumbotron">
#### 2021
{% bibliography --query @article[year=2021] %}
</div>

<div class="jumbotron">
#### 2020
{% bibliography --query @article[year=2020] %}
</div>

<div class="jumbotron">
### Book chapters, preprints and other miscellaneous
{% bibliography --query !@article[year>=2020] %}
</div>
