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

<body id="fellows-body">

  <div id="wrapper">
      <div class="right-border-box" id="fellows-border-box">
        <div class="intro-text" id="fellows-setup">

          <h3>{{ site.data.fellows-setup.title }}</h3>
          <p>{{ site.data.fellows-setup.copy }}</p>
        </div>
      </div>

      
      <div id="fellows-backdrop">
        <div id="fellows">
            {% for item in site.data.fellows %}
              <div class="fellow">
                <div class="fellow-headshot" style="background-image: url( {{ item.background }} );">
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

  
</body>      





