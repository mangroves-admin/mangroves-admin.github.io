---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: give
title: Give
permalink: /give/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <!-- <link rel="stylesheet" type="text/css" href="/css/readmore-styles.css" />
    <link rel="stylesheet" type="text/css" href="/css/styles.css" /> -->
</head>

<body id="give-body">
    <div id="give-wrapper">

        <div class="info-block" id="give-main">
            <div class="right-border-box-dark" id="give-border-box">

            
                <div class="think-page-section" id="give-main-section">

                    {% for item in site.data.give-subpage %}
                        <div class="think-item">
                            <div class="section-title" id="give-item-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div class="do-info" id="give-info">
                                <p>{{ item.copy }}</p>
                            </div>
                        </div>
                    {% endfor %}

                    <div class="intro-image-wrapper">
                        <div class="intro-text" id="give-image">
                            <div class="image-with-credit" id="giving-tree-image">
                                <img src="/design/img/subpage-img/tree-birds.png" alt="the-giving-tree">
                                <div class="photo-credit" id="give-photo-credit">
                                    <p>Sutirta BudimanCRALDIEZ</p>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>        
    </div>
    
</body>