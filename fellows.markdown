---
layout: fellows
title: Mangroves Pilot Fellows
year: 2022/2023
permalink: /fellows/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="fellows-body">
  <div id="wrapper">

    <div class="info-block" id="fellows-intro-block">
      <div class="right-border-box" id="fellows-border-box">
        <div class="intro-text" id="fellows-setup">
          <h3>{{ site.data.fellows-setup.title }}</h3>
          <p>{{ site.data.fellows-setup.copy }}</p>
        </div>
      </div>
    </div>



    <div class="right-border-box-dark">
      <div class="info-block" id="summary-2122-info-block">
        <div class="think-item" id="summary-2122-section">
          <div class="section-title" id="fellows2425-item-title">
            <h3>2024-25: Intelligence</h3>
          </div>

            <div class="intro-image-wrapper">
              <div class="intro-text" id="fellows-2425-image">
                <img src="/design/img/fellowship-screenshots/fellowship-intelligence.png" alt="fellows-2223-screenshot">
              </div>
            </div>
        </div>


        {% for item in site.data.fellows-summary-24-25 %}
          <div class="three-column-fellows">
            <div class="margin-column left-margin">
              <div class="marginal-blurb">
                <p style="color: {{ item.left-blurb-1-color }}">{{ item.left-blurb-1 }}</p>
                <p style="color: {{ item.left-blurb-2-color }}">{{ item.left-blurb-2 }}</p>
                <p style="color: {{ item.left-blurb-3-color }}">{{ item.left-blurb-3 }}</p>
              </div>
            </div>

            <div class="think-info-wrapper fellows-wrapper">

              <!-- <div class="think-item fellows-summary-section" id="summary-2425-section">
              </div> -->

                <div class="fellows-subpage-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div class="fellows-subpage-info">
                  <p>{{ item.copy }}</p>
                </div>
            </div>

              <div class="margin-column right-margin">
                <div class="marginal-blurb">
                  <p style="color: {{ item.right-blurb-1-color }}">{{ item.right-blurb-1 }}</p>
                  <p style="color: {{ item.right-blurb-2-color }}">{{ item.right-blurb-2 }}</p>
                  <p style="color: {{ item.right-blurb-3-color }}">{{ item.right-blurb-3 }}</p>
                </div>
              </div>
          </div>
        {% endfor %}

        <div class="think-item" id="reading-list-2425">
          <div class="reading-list-links" id="2425-reading-list-links">
                <h4><a href="../fellows/reading-list-2223.html" target="_blank">Reading List (with links)</a></h4>
                <h4><a href="../content/pilot-fellowship/reading-list-2223.pdf" target="_blank">Reading List (PDF)</a></h4>
          </div>
        </div>
      </div>
        

      <div class="info-block">
          <!-- <div class="right-border-box-dark"> -->
            <div class="think-item">
              <div class="section-title " id="fellows-2425-bios-title">
                <h3>Mangroves Pilot Fellows 2024-25</h3>
              </div>
            </div>
            
            <div id="fellows-2425">

              {% for item in site.data.fellows-24-25 %}
              <div class="three-column">

                <div class="margin-column left-margin">
                  <div class="marginal-blurb">
                    <p style="color: {{ item.left-blurb-1-color }}">{{ item.left-blurb-1 }}</p>
                    <p style="color: {{ item.left-blurb-2-color }}">{{ item.left-blurb-2 }}</p>
                    <p style="color: {{ item.left-blurb-3-color }}">{{ item.left-blurb-3 }}</p>
                  </div>
                </div>

                <div class="fellow">
                  <div class="fellow-headshot" style="background-image: url( {{ item.background }} );">
                    <!-- <img src="{{ item.background }}"> -->
                    <!-- </div> -->
                  </div>
                  <div class="fellow-bio">
                    <h3>{{ item.name }}</h3>
                    <p>{{ item.bio }}</p>
                  </div>
                </div>

                 <div class="margin-column right-margin">
                    <div class="marginal-blurb">
                      <p style="color: {{ item.right-blurb-1-color }}">{{ item.right-blurb-1 }}</p>
                      <p style="color: {{ item.right-blurb-2-color }}">{{ item.right-blurb-2 }}</p>
                      <p style="color: {{ item.right-blurb-3-color }}">{{ item.right-blurb-3 }}</p>
                    </div>
                  </div>
              </div>
              {% endfor %}
            </div>
      </div>
      </div>



        <!-- </div> -->
      <!-- </div> -->
      <!-- </div> -->
    <!-- </div> -->
      <!-- </div> -->


    
    <div class="right-border-box-dark">
      <div class="info-block" id="summary-2122-info-block">
        <div class="think-item" id="summary-2122-section">
          <div class="section-title" id="fellows2223-item-title">
            <h3>2022-23: Growth</h3>
          </div>

            <div class="guest-discussants">
              <h4>Guest Discussants:</h4>
              <p>Dilip da Cunha (ubiquitous wetness) - Arturo Escobar and Michal Osterweil (relationality) -  Bruce Lawrence (Ibn Khaldun's historic cycles) - Daniel Richter (critical zone science) - Antonio Tamburrino (Carless Rome)</p>
            </div>

            <div class="intro-image-wrapper">
              <div class="intro-text" id="fellows-2223-image">
                <img src="/design/img/fellowship-screenshots/2022-23-1.jpeg" alt="fellows-2223-screenshot">
              </div>
            </div>
        </div>


        {% for item in site.data.fellows-summary-22-23 %}
          <div class="three-column">
            <div class="margin-column left-margin">
              <div class="marginal-blurb">
                <p style="color: {{ item.left-blurb-1-color }}">{{ item.left-blurb-1 }}</p>
                <p style="color: {{ item.left-blurb-2-color }}">{{ item.left-blurb-2 }}</p>
                <p style="color: {{ item.left-blurb-3-color }}">{{ item.left-blurb-3 }}</p>
              </div>
            </div>

            <div class="think-info-wrapper fellows-wrapper">

              <!-- <div class="think-item fellows-summary-section" id="summary-2223-section">
              </div> -->

                <div class="fellows-subpage-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div class="fellows-subpage-info">
                  <p>{{ item.copy }}</p>
                </div>
            </div>

              <div class="margin-column right-margin">
                <div class="marginal-blurb">
                  <p style="color: {{ item.right-blurb-1-color }}">{{ item.right-blurb-1 }}</p>
                  <p style="color: {{ item.right-blurb-2-color }}">{{ item.right-blurb-2 }}</p>
                  <p style="color: {{ item.right-blurb-3-color }}">{{ item.right-blurb-3 }}</p>
                </div>
              </div>
          </div>
        {% endfor %}

        <div class="think-item" id="reading-list-2223">
          <div class="reading-list-links" id="2223-reading-list-links">
                <h4><a href="../fellows/reading-list-2223.html" target="_blank">Reading List (with links)</a></h4>
                <h4><a href="../content/pilot-fellowship/reading-list-2223.pdf" target="_blank">Reading List (PDF)</a></h4>
          </div>
        </div>
      </div>
        

      <div class="info-block">
          <!-- <div class="right-border-box-dark"> -->
            <div class="think-item">
              <div class="section-title " id="fellows-2223-bios-title">
                <h3>Mangroves Pilot Fellows 2022-23</h3>
              </div>
            </div>
            
            <div id="fellows-2223">

              {% for item in site.data.fellows %}
              <div class="three-column">

                <div class="margin-column left-margin">
                  <div class="marginal-blurb">
                    <p style="color: {{ item.left-blurb-1-color }}">{{ item.left-blurb-1 }}</p>
                    <p style="color: {{ item.left-blurb-2-color }}">{{ item.left-blurb-2 }}</p>
                    <p style="color: {{ item.left-blurb-3-color }}">{{ item.left-blurb-3 }}</p>
                  </div>
                </div>

                <div class="fellow">
                  <div class="fellow-headshot" style="background-image: url( {{ item.background }} );">
                    <!-- <img src="{{ item.background }}"> -->
                    <!-- </div> -->
                  </div>
                  <div class="fellow-bio">
                    <h3>{{ item.name }}</h3>
                    <p>{{ item.bio }}</p>
                  </div>
                </div>

                 <div class="margin-column right-margin">
                            <div class="marginal-blurb">
                                <p style="color: {{ item.right-blurb-1-color }}">{{ item.right-blurb-1 }}</p>
                                <p style="color: {{ item.right-blurb-2-color }}">{{ item.right-blurb-2 }}</p>
                                <p style="color: {{ item.right-blurb-3-color }}">{{ item.right-blurb-3 }}</p>
                            </div>
                        </div>
              </div>
              {% endfor %}
            </div>
      </div>
      </div>



        <!-- </div> -->
      <!-- </div> -->
      <!-- </div> -->
    <!-- </div> -->
      <!-- </div> -->






    <div class="right-border-box-dark" id="summary-2122-border-box">
      <div class="think-item" id="summary-2122-section">
          <div class="section-title" id="fellows2122-item-title">
            <h3>2021-22: The Common and the Commonable</h3>
          </div>

          <div class="guest-discussants">
            <h4>Guest Discussants:</h4>
            <p>Roxana Bendezú (migrant experience/media) - Chiara Klein (community fisheries) - Bruce Lawrence (Islamicate cosmopolitanism) - Lissa McCullough (Soleri's arcology) - Stuart Pimm (bioconservation)</p>
          </div>

          <div class="intro-image-wrapper">
            <div class="intro-text" id="fellows-2122-image">
              <img src="../design/img/fellowship-screenshots/2021-22-1.png" alt="fellows-2122-screenshot">
            </div>
          </div>
        </div>  


         {% for item in site.data.fellows-summary-21-22 %}
          <div class="three-column">
            <div class="margin-column left-margin">
              <div class="marginal-blurb">
                <p style="color: {{ item.left-blurb-1-color }}">{{ item.left-blurb-1 }}</p>
                <p style="color: {{ item.left-blurb-2-color }}">{{ item.left-blurb-2 }}</p>
                <p style="color: {{ item.left-blurb-3-color }}">{{ item.left-blurb-3 }}</p>
              </div>
            </div>

            <div class="think-info-wrapper fellows-wrapper">

              <!-- <div class="think-item" id="summary-2122-section">
              </div> -->

                <div class="fellows-subpage-title">
                    <h3>{{ item.title }}</h3>
                </div>
                <div class="fellows-subpage-info">
                  <p>{{ item.copy }}</p>
                </div>
            </div>

              <div class="margin-column right-margin">
                <div class="marginal-blurb">
                  <p style="color: {{ item.right-blurb-1-color }}">{{ item.right-blurb-1 }}</p>
                  <p style="color: {{ item.right-blurb-2-color }}">{{ item.right-blurb-2 }}</p>
                  <p style="color: {{ item.right-blurb-3-color }}">{{ item.right-blurb-3 }}</p>
                </div>
              </div>
          </div>
        {% endfor %}
          
          <div class="think-item" id="reading-list-2122">
            <div class="reading-list-links" id="2122-reading-list-links">
              <h4><a href="../fellows/reading-list-2122.html" target="_blank">Reading List (with links)</a></h4>
              <h4><a href="../content/pilot-fellowship/reading-list-2122.pdf" target="_blank">Reading List (PDF)</a></h4>
            </div>
          </div>

          <div id="fellows-2122">

            <div id="fellows-2122-text">
              <div class="section-title" id="fellows-2122-bios-title">
                <h3>Mangroves Pilot Fellows 2021-22</h3>
              </div>

              <div id="fellows-2122-bios">
                  <div id="fellows-2122-bios-copy">
                    {% for item in site.data.fellows-21-22 %}
                      <div class="fellow-previous-year">
                        <h4>{{ item.name }}</h4>
                        <p>{{ item.profession }}</p>
                      </div>
                    {% endfor %}
                  </div>
              </div>  
            </div>

            <div id="depth-of-being-painting">
              <img src="/design/img/subpage-img/depth-of-being.jpg" alt="depth-of-being-painting">
              <p>Painting by Deborah Patterson, used by permission</p>
            </div>
          <!-- </div> -->
      </div>
        <!-- </div> -->
    </div>





    
    <div class="right-border-box-dark">
      <div class="think-item" id="fellows">
        <div id="fellows-responses">
          <div class="section-title" id="fellows-responses-title">
            <h3>Responses to the Fellowship:</h3>
          </div>

          <div id="responses-copy">
            <div id="responses-img">
                  <div class="response-photo-with-credit">
                    <img src="/design/img/subpage-img/fellows-skyshot.jpg" alt="trees-skyshot">
                    <div class="photo-credit" id="responses-photo-credit">
                      <p>Mohamed Ibrahim</p>
                    </div>
                  </div>

                  <div class="response-photo-with-credit">
                    <img src="/design/img/subpage-img/stone-road.jpg" alt="stone-road">
                  </div>

                  <div class="response-photo-with-credit">
                    <img src="/design/img/subpage-img/reflection.jpeg" alt="reflection">
                  </div>

                    <!-- <img src="/design/img/subpage-img/reflection.jpeg" alt="reflection"> -->
                </div>

                {% for item in site.data.fellows-responses %}
                  <div class="fellows-response">
                    <p>{{ item.copy }}</p>
                    <h4>&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;{{ item.name }}</h4>
                  </div>
                {% endfor %}
            </div>
          </div>
      </div>
    </div>





  </div>
</body>      


