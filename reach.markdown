---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: readmore
title: Reach
permalink: /reach/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="reach-body">
    <div id="wrapper">
        <div class="right-border-box" id="reach-border-box">

        <div class="section-title" id="think-section-title">
            <h3>Reach</h3>
        </div>

            <div id="do-page-section">
            <div id="reach-intro">
            <p>Initiatives we are currently learning through:</p>
            </div>
                {% for item in site.data.reach-subpage %}

                <div class="initiative">
                    <div class="initiative-logo">
                        <img src="../design/img/logo-draft.png">
                    </div>
                    <div class="reach-item">
                        <div class="reach-title">
                            <a href="{{ item.url }}">
                                <h3>{{ item.title }}</h3>
                            </a>
                        </div>
                        <div class="do-info">
                            <p>{{ item.copy }}</p>
                        </div>
                    </div>
                </div>


                {% endfor %}
            </div>
        </div>
    </div>
</body>