---
layout: fellows
title: Mangroves Pilot Fellows
year: 2022/2023
permalink: /fellows/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
</head>


  <div id="wrapper">
  <div id="fellows-backdrop">
    <div id="fellows">
        {% for item in site.data.fellows %}
          <div class="fellow">
            <div class="fellow-headshot" style="background-image: url( {{ item.background }} );"></div>
            <div class="fellow-bio">
              <h3>{{ item.name }}</h3>
              <p>{{ item.bio }}</p>
            </div>
          </div>
        {% endfor %}
      </div>
    </div>
  <!-- <div id="flower-box">
    <div class="blue-flower left-flower" id="flower-1"></div>
    <div class="blue-flower" id="flower-2"></div>
    <div class="blue-flower" id="flower-3"></div>
    <div class="blue-flower" id="-flower-4"></div>
    <div class="blue-flower" id="-flower-5"></div>
    <div class="blue-flower" id="-flower-6"></div>
    <div class="blue-flower" id="-flower-7"></div>
    <div class="blue-flower" id="-flower-8"></div>
    <div class="blue-flower" id="-flower-7"></div>
    <div class="blue-flower" id="-flower-8"></div>
  </div> -->
</div>




