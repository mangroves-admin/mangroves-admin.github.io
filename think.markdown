---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: readmore
title: Think
permalink: /think/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
</head>

<body id="think-body">
    <div id="wrapper">
    
        
        <div class="info-block" id="basal-block">
            <div class="right-border-box" id="basal-border-box">
            
                <div class="section-title" id="think-subpage-title">
                    <h3>Think</h3>
                </div>
               
                <div class="think-page-section" id="basal-thought">
                    

                    {% for item in site.data.basal-thought %}
                    <div class="think-item">
                            <div class="think-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div id="mobius-loop">
                                <img src="/design/img/subpage-img/mobius.png" alt="mobius-loop">
                            </div>
                            <div class="think-info">
                                <p>{{ item.copy }}</p>
                            </div>
                    </div>
                    {% endfor %}
                </div>
            </div>
        </div>

        <div class="intro" id="spaceholder">
            <div class="right-border-box" id="home-intro-box">
                <div id="spaceholder"></div>
            </div>
        </div>

        <div class="info-block" id="periblem-block">
            <div class="right-border-box" id="periblem-border-box">
                <div class="think-page-section" id="periblem-vs-problem">
                    {% for item in site.data.periblem-vs-problem %}
                    <div class="think-item">
                        <div class="think-info" id="periblem-info">
                            <div class="think-title">
                                <h3>{{ item.title }}</h3>
                            </div>
                            <div class="think-info">
                                <div id="periblem-image">
                                    <img src="/design/img/subpage-img/sand.jpeg" alt="sand-photo">
                                    <div class="photo-credit" id="periblem-photo-credit">
                                        <p>Julia Kane</p>
                                    </div>
                                </div>
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
                            <div class="think-info" id="counterdesign-info">
                                <div id="chandelier-painting">
                                    <img src="/design/img/subpage-img/chandelier-lb.jpg" alt="chandelier-painting">
                                    <p>Chandelier <i>by Lisa Brody, used by permission</i></p>
                                </div>
                                <p>{{ item.copy }}</p>
                            </div>
                    </div>
                    {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="copyright-block">
            <div class="right-border-box" id="copyright-border-box">
                    <div class="think-page-section" id="copyright-section">
                            <div class="think-item" id="think-copyright">
                                <p>© David U.B. Liu 2023</p>
                            </div>
                    </div>
            </div>
        </div>
<!-- 
        <div class="info-block" id="chandelier-block">
            <div class="right-border-box" id="chandelier-border-box">
                <div id="chandelier-painting">
                    <img src="/design/img/subpage-img/chandelier-lb.jpg" alt="chandelier-painting">
                    <p><i>Chandelier</i> by Lisa Brody, used by permission</p>
                </div>
            </div>
        </div> -->



    </div>
</body>