---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: readmore
title: Think
permalink: /think/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="think-body">
    <div id="wrapper">
    
        
        <div class="info-block" id="basal-block">
            <div class="right-border-box" id="basal-border-box">
            
                <div class="section-title" id="think-section-title">
                    <h3>Think</h3>
                </div>
               
                <div class="think-page-section" id="basal-thought">
                    

                    {% for item in site.data.basal-thought %}
                    <div class="think-item">
                            <div class="think-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div class="think-info">
                                <p>{{ item.copy }}</p>
                            </div>
                    </div>
                    {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="periblem-block">
            <div class="right-border-box" id="periblem-border-box">
                <div class="think-page-section" id="periblem-vs-problem">
                    {% for item in site.data.periblem-vs-problem %}
                    <div class="think-item">
                        <div class="think-info">
                            <div class="think-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div class="think-info">
                                <p>{{ item.copy }}</p>
                            </div>
                        </div>
                    </div>
                    {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="counterdesign-block">
            <div class="right-border-box" id="counterdesign-border-box">
                <div class="think-page-section" id="deep-counterdesign">
                    {% for item in site.data.deep-counterdesign %}
                    <div class="think-item">
                            <div class="think-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div class="think-info">
                                <p>{{ item.copy }}</p>
                            </div>
                    </div>
                    {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="copyright-block">
            <div class="right-border-box" id="copyright-border-box">
                <div class="think-page-section" id="deep-counterdesign">
                    <div class="think-item" id="think-copyright">
                        <div class="think-info">
                            <p>© David U.B. Liu 2023</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- <div class="info-block" id="chandelier-block">
            <div class="right-border-box" id="chandelier-border-box">
                <div id="chandelier-painting">
                    <img src="/design/img/chandelier-lb.jpg" alt="chandelier-painting">
                    <p><i>Chandelier</i> by Lisa Brody, used by permission</p>
                </div>
            </div>
        </div> -->



    </div>
</body>