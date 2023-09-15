---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: connival
title: Connival On Growth
permalink: /connival/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
    
</head>

<body id="connival-body">
  <div id="wrapper">
    <div class="info-block" id="connival-block">
      <div class="right-border-box right-border-box-dark" id="right-border-box-connival">
        <h4>"Connival on Growth," TBA, Rome - a Spicy Hint:</h4>

        <div class="responsive-two-columns" id="connival-main">
          <div id="connival-column-1-1">
            <p>{{ site.data.connival.copy }}</p>
          </div>
          <div id="connival-column-1-2">
            <div id="connival-main-img-container">
              <img src="/design/img/rome-houses.jpg" />
            </div>
          </div>
        </div>
      </div>

      <div class="right-border-box right-border-box-dark" id="right-border-box-proceedings">
        <div class="responsive-two-columns" id="connival-proceedings">
          <div id="connival-column-2-1">
            <div id="draft-proc-img-container">
              <img src="/design/img/connival-dl.jpeg">
            </div>
          </div>
          <div id="connival-column-2-2">
            <div class="section-title" id="draft-proceedings-title">
              <h3>{{ site.data.connival-proceedings.title }}</h3>
            </div>
            <p>{{ site.data.connival-proceedings.copy }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>