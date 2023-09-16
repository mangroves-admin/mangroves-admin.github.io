---
layout: fellows
title: Mangroves Pilot Fellows
year: 2022/2023
permalink: /fellows/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="fellows-body">
  <div id="wrapper">

    <div class="info-block" id="fellows-intro-block">
      <div class="right-border-box" id="fellows-border-box">
        <div class="intro-text" id="fellows-setup">
          <h3>{{ site.data.fellows-setup.title }}</h3>
          <p>{{ site.data.fellows-setup.copy }}</p>
        </div>
      </div>
    </div>
    
    <div class="info-block" id="summary-2122-info-block">

      <div class="right-border-box-dark" id="summary-2122-border-box">
        <div class="think-item" id="summary-2122-section">
          <div class="section-title" id="fellows2122-item-title">
            <h3>2021-22: The Common and the Commonable</h3>
          </div>

        <div class="guest-discussants">
          <h4>Guest Discussants:</h4>
          <p>Roxana Bendezú (migrant experience/media) - Chiara Klein (community fisheries) - Bruce Lawrence (Islamicate cosmopolitanism) - Lissa McCullough (Soleri's arcology) - Stuart Pimm (bioconservation)</p>
        </div>

        {% for item in site.data.fellows-summary-21-22 %}
        <!-- no subtitles in 2021-2022 summary: can easily add later if you wish -->
          <!-- <div class="fellows-subpage-title">
            <h3>
              {{ item.title }}
            </h3>
          </div> -->
          <div class="fellows-subpage-info">
            <p>
              {{ item.copy}}
            </p>
          </div>
        {% endfor %}

        </div>
      </div>

      <div class="right-border-box-dark" id="summary-2223-border-box">
        <div class="think-item" id="summary-2223-section">
          <div class="section-title" id="fellows2223-item-title">
            <h3>2022-23: Growth</h3>
          </div>

        <div class="guest-discussants">
          <h4>Guest Discussants:</h4>
          <p>Dilip da Cunha (ubiquitous wetness) - Arturo Escobar and Michal Osterweil (relationality) -  Bruce Lawrence (Ibn Khaldun's historic cycles) - Daniel Richter (critical zone science) - Antonio Tamburrino (Carless Rome)</p>
        </div>

        {% for item in site.data.fellows-summary-22-23 %}
          <div class="fellows-subpage-title">
            <h3>
              {{ item.title }}
            </h3>
          </div>
          <div class="fellows-subpage-info">
            <p>
              {{ item.copy}}
            </p>
          </div>
        {% endfor %}

        </div>
      </div>
    </div>


    <div class="info-block">
      <div class="right-border-box-dark">
        <div id="fellows">
          {% for item in site.data.fellows %}
            <div class="fellow">
              <div class="fellow-headshot" style="background-image: url( {{ item.background }} );">
                <!-- <img src="{{ item.background }}"> -->
                <!-- </div> -->
              </div>
              <div class="fellow-bio">
                <h3>{{ item.name }}</h3>
                <p>{{ item.bio }}</p>
              </div>
            </div>
          {% endfor %}
        </div>
      </div>
    </div>

    <div class="info-block">
      <div class="right-border-box-dark" id="responses-border-box">
        <p>Obez</p>
      </div>
    </div>




  </div>
</body>      


