---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: mangroves-home
title: Connival On Growth
permalink: /connival-on-growth/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
</head>

 <div id="wrapper">
    <div id="think-section">
        {% for item in site.data.think %}
        <div id="think-item">
            <div class="yay">
                <div class="think-title">
                     <h3>{{ item.title }}</h3>
                </div>
                <div class="think-info">
                    <p>{{ item.copy }}</p>
                    <a href="{{ item.url }}"><h4>Read more |</h4></a>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>
</div>