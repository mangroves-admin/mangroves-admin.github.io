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
        <div class="intro-text" id="summary-2122-section">
          <div class="section-title" id="fellows2122-item-title">
            <h3>HEEHEE GANDALF.....YOUR STAFF IS CURVED TO THE RIGHT</h3>
          </div>
          <p>Mangroves launched its Pilot Fellowship with the theme “the Common and the Commonable.” The notion of the common might at first recall something mundane, resourceable, exploitable - or public. The commonable might evoke rocky grass fields or animals grazing with bent necks on sharable land. Both might be reduced to some objectified commons. Our path, however, was to expand from this legacy of the common and commonable, asking what they might signify when freed from such contexts.</p>
        </div>
      </div>

      <div class="right-border-box-dark" id="summary-2223-border-box">
        <div class="intro-text" id="summary-2223-section">
          <div class="section-title" id="fellows2223-item-title">
            <h3>HOHO SAROOMUN.....YOUR STAFF IS BROKEN</h3>
          </div>
          <p>Mangroves launched its Pilot Fellowship with the theme “the Common and the Commonable.” The notion of the common might at first recall something mundane, resourceable, exploitable - or public. The commonable might evoke rocky grass fields or animals grazing with bent necks on sharable land. Both might be reduced to some objectified commons. Our path, however, was to expand from this legacy of the common and commonable, asking what they might signify when freed from such contexts.</p>
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


