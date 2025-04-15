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

            <div class="section-title" id="reach-subpage-title">
                <h3>Reach</h3>
            </div>
            
            
            <div class="three-column">


                <div class="margin-column left-margin">
                    <div class="marginal-blurb">
                        <p style="color: rgb(217, 192, 28)"><br><br><br>how do others help us travel further?</p>
                        <p style="color: rgb(1,1,1)"></p>
                        <p style="color: rgb(1,1,1)"></p>
                    </div>
                </div>

                <div class="think-page-section" id="reach-page-main">
                    <div class="think-info" id="reach-intro">
                        <p>Initiatives we are currently learning through:</p>
                    </div>

                    <div class="think-info">
                        
                        {% for item in site.data.reach-subpage %}
                            <div class="initiative">
                                <div class="initiative-logo" id="{{ item.logo-id }}">
                                    <img src='{{ item.logo }}'>
                                </div>
                                <div class="reach-item" id="{{ item.id }}">
                                    <div class="reach-title">
                                        <a href="{{ item.url }}" target="_blank">
                                            <h3>{{ item.title }}</h3>
                                        </a>
                                    </div>
                                    <div class="reach-info">
                                        <p>{{ item.copy }}</p>
                                    </div>
                                </div>
                            </div>
                        {% endfor %}

                    </div>
                </div>

                <div class="margin-column right-margin">
                    <div class="marginal-blurb">
                        <p style="color: rgb(254, 79, 167)"><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>it's not just about us</p>
                        <p style="color: rgb(1,1,1)"></p>
                        <p style="color: rgb(1,1,1)"></p>
                    </div>
                </div>
            </div>
        
        
        
        </div>
    </div>
</body>