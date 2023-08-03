---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: mangroves-home
title: Mangroves
permalink: /do/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
</head>

    <div id="do-section">
        {% for item in site.data.do %}
        <div id="do-item">
            <div class="yay">
                <div class="do-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div class="do-info">
                    <p>{{ item.copy }}</p>
                    <a href="{{ item.url }}"><h4>Read more |</h4></a>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>



    <div id="contact-section">
        <div id="contact-us">
        <div id="blue-flower-contact">
        </div>
        <div id="mailbox">
             <div class="corner-art" id="curly-mailbox-top-left">
                <img src="../design/img/dec-border.svg" alt="curlicue-mailbox-top-left">
            </div>
            <div class="corner-art" id="curly-mailbox-top-right">
                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
            </div>
            <div class="corner-art" id="curly-mailbox-bottom-left">
                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
            </div>
            <div class="corner-art" id="curly-mailbox-bottom-right">
                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
            </div>
            <h4>contact us at:</h4>
            <h3>info@mangroves.life</h3>
        </div>
        <div id="social-media">
            <div class="social-icon" id="linkedin"></div>
            <div class="social-icon" id="twitter"></div>
            <div class="social-icon" id="mastodon"></div>
        </div>
        </div>
    </div>
</div>