---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: give
title: Give
permalink: /give/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />


<body id="give-body">
    <div id="wrapper">
        <div class="right-border-box-dark" id="give-border-box">
            <div class="do-page-section" id="give-main-section">
                {% for item in site.data.give-subpage %}
                <div id="do-item">
                    <div class="main-copy">
                        <div class="do-title">
                            <h3>{{ item.title }}</h3>
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