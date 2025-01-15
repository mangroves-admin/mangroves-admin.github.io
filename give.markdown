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
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />

<body id="give-body">
    <div id="give-wrapper">

        <div class="info-block" id="give-main">
            <div class="right-border-box-dark" id="give-border-box">


                <div class="think-page-section" id="give-main-section">

                    <!-- <div class="think-page-section" id="give-main-content-wrapper"> -->
                        {% for item in site.data.give-subpage %}
                            <div class="give-item">
                                <div class="section-title" id="give-subpage-title">
                                    <h3>{{ item.title }}</h3>
                                </div>
                                <div id="give-info">
                                    <p>{{ item.copy }}</p>
                                </div>
                            </div>
                        {% endfor %}

                        <div class="section-title" id="donate-here-title">
                            <h3>Donate Here</h3>
                            <p>We cordially thank you!</p>
                        </div>


                        <div class="donation-widget">
                            <!-- simple donation widget -->
                            <script>gl=document.createElement('script');gl.src='https://secure.givelively.org/widgets/simple_donation/mangroves.js?show_suggested_amount_buttons=true&show_in_honor_of=false&address_required=false&has_required_custom_question=null&suggested_donation_amounts[]=50&suggested_donation_amounts[]=100&suggested_donation_amounts[]=500&suggested_donation_amounts[]=1000';document.getElementsByTagName('head')[0].appendChild(gl);</script><div id="give-lively-widget" class="gl-simple-donation-widget"></div>
                            <!-- end donation widget -->

                            <!-- branded donation widget -->
                            <!-- <script>gl=document.createElement('script');gl.src='https://secure.givelively.org/widgets/branded_donation/mangroves.js';document.getElementsByTagName('head')[0].appendChild(gl);</script><div data-widget-src='https://secure.givelively.org/donate/mangroves?ref=sd_widget' id="give-lively-widget" class="gl-branded-donation-widget"></div> -->
                            <!-- end donation widget -->
                        </div>

                    <div class="intro-image-wrapper">
                        <div class="intro-text" id="give-image">
                            <div class="image-with-credit" id="giving-tree-image">
                                <img src="/design/img/subpage-img/tree-birds.png" alt="the-giving-tree">
                                <div class="photo-credit" id="give-photo-credit">
                                    <p>Sutirta Budiman</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>

