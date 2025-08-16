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
th, td {
    padding-left: 10px;
    padding-right: 10px;
    padding-top: 4px;
    padding-bottom: 4px;
    text-align: center;
}
</style>

### Refereed journal articles

<table>
  <tr>
    <td><span style="color:#AC0214;font-weight:bold;">NJIT Biology faculty.</span></td>
    <td><span style="color:#2E5984;font-weight:bold;">NJIT graduate student.</span></td>
    <td><span style="color:#E05E2F;font-weight:bold;">NJIT post-doctoral researcher.</span><br></td>
  </tr>
  <tr>
    <td><span style="color:#AC0214;">Other NJIT faculty.</span></td>
    <td><span style="color:#2E5984;">NJIT undergraduate student.</span></td>
    <td><span style="color:#3C6530;">External student.</span></td>
  </tr>
  </table>

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

### Conference proceedings, book chapters, etc.
<div class="jumbotron">
### All since 2020
{% bibliography --query !@article[year>=2020] %}
</div>
