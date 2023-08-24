---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: meet
title: Meet
permalink: /meet/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="meet-body">
    <div id="wrapper">

        <div class="info-block" id="directors-border-box">
            <div class="right-border-box">
                <div class="section-title meet-section" >
                    <h3>Board of Directors</h3>
                </div>
                <div class="do-page-section" id="board-of-directors">
                    {% for item in site.data.directors %}
                    <div class="faculty">
                        <div class="faculty-headshot" style="background-image: url( {{ item.img }} );"></div>
                        <div class="faculty-bio">
                        <p><b>{{ item.name }}</b> {{ item.bio }}</p>
                    </div>
                </div>
                {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="advisory-border-box">
            <div class="right-border-box">
                <div class="section-title">
                    <h3>Advisory Board</h3>
                </div>
                <div class="do-page-section" id="board-of-directors">
                    {% for item in site.data.advisory %}
                    <div class="faculty">
                        <div class="faculty-headshot" style="background-image: url( {{ item.img }} );"></div>
                        <div class="faculty-bio">
                        <p><b>{{ item.name }}</b> {{ item.bio }}</p>
                    </div>
                </div>
                {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="personnel-border-box">
            <div class="right-border-box">
            <div class="section-title">
                <h3>Personnel</h3>
            </div>
                <div class="do-page-section" id="board-of-directors">
                    {% for item in site.data.personnel %}
                    <div class="faculty">
                        <div class="faculty-headshot" style="background-image: url( {{ item.img }} );"></div>
                        <div class="faculty-bio">
                        <p><b>{{ item.name }}</b> {{ item.bio }}</p>
                    </div>
                </div>
                {% endfor %}
                </div>
            </div>
        </div>

    </div>
</body>