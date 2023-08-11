---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: mangroves-home
title: Mangroves
permalink: /home/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
</head>

<div id="wrapper">

    <div class="intro">
        <div class="right-border-box">
            <div class="intro-text">
                <p><span>Mangroves</span> is a do-think tank. We are small, dreaming big - though never alone. We are concerned with long planetary futures. Our model of a collaboratory is to engender coworking in-house with staff and annual fellows, with persons and organizations outside of our collab, as well as non-human <i>coactants</i> - always!</p>
            </div>
        </div>
    </div>


    <div class="info-block" id="think-section">
        <div class="right-border-box">
            <div class="section-title">
                <h3>Think</h3>
            </div>
            {% for item in site.data.think %}
                <div id="think-item">
                    <div class="think-title">
                        <h3>{{ item.title }}</h3>
                    </div>
                    <div class="think-info">
                        <p>{{ item.copy }}</p>
                        <a href="{{ item.url }}"><h4>Read more |</h4></a>
                    </div>
                </div>
            {% endfor %}
        </div>
    </div>

    <div class="info-block" id="do-section">
        <div class="right-border-box">
            <div class="section-title">
                <h3>Do</h3>
                <h4>Current Projects</h4>
            </div>
            {% for item in site.data.do %}
                <div id="do-item">
                    <div class="do-title">
                        <h3>{{ item.title }}</h3>
                    </div>
                    <div class="do-info">
                        <p>{{ item.copy }}</p>
                        <a href="{{ item.url }}"><h4>Read more |</h4></a>
                    </div>
                </div>
            {% endfor %}
        </div>
    </div>



    <div class="info-block" id="stretching-forth">
        <div class="right-border-box">
        <div id="blue-flower-contact">
        </div>
            <div class="intro" id="stretching-forth-text">
                {% for item in site.data.stretching-forth %}
                    <h3>{{ item.title }}</h3>
                    <p>{{ item.copy }}</p>
                {% endfor %}
            </div>
        </div>
    </div>

    <!-- <div class="info-block" id="meet-section">
        <div class="right-border-box" id="meet-border-box">
            <div class="intro" id="meet-text">
                {% for item in site.data.meet %}
                <div class="section-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div id="do-item">
                    <div class="do-info">
                        <p>{{ item.copy }}</p>
                        <a href="{{ item.url }}"><h4>Read more |</h4></a>
                    </div>
                </div>
            {% endfor %}
            </div>
        </div>
    </div>

    <div class="info-block" id="reach-section">
        <div class="right-border-box" id="reach-border-box">
            <div class="intro" id="reach-text">
                {% for item in site.data.reach %}
                <div class="section-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div id="do-item">
                    <div class="do-info">
                        <p>{{ item.copy }}</p>
                    </div>
                </div>
            {% endfor %}
            </div>
        </div>
    </div>

    <div class="info-block" id="give-section">
        <div class="right-border-box" id="give-border-box">
            <div class="intro" id="give-text">
                {% for item in site.data.give %}
                <div class="section-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div id="do-item">
                    <div class="do-info">
                        <p>{{ item.copy }}</p>
                        <a href="{{ item.url }}"><h4>Give |</h4></a>
                    </div>
                </div>
            {% endfor %}
            </div>
        </div>
    </div> -->






    




    <div class="info-block" id="contact-section">
        <div class="right-border-box" id="contact-border-box">
        <div id="contact-us">
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
                <h3>tidings@mangroves.life</h3>
            </div>

            <div id="social-media">
                <div class="social-icon" id="linkedin"></div>
                <div class="social-icon" id="twitter"></div>
                <div class="social-icon" id="mastodon"></div>
            </div>
        </div>
        </div>
    </div>
</div>
