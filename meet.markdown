---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: meet
title: Meet
permalink: /meet/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/readmore-styles.css" />
</head>

<body id="meet-body">
    <div id="wrapper">

        <div class="info-block" id="meet-intro">
            <div class="right-border-box">

            <div class="section-title" id="meet-section-title">
                <h3>Meet</h3>
            </div>

                <div class="meet-item" id="meet-intro-boards">
                    <div class="section-subtitle" id="boards-section-title">
                        <h3>Boards</h3>
                    </div>
                    <p>Our Board of Directors oversees strategy, governance, and audit of the Collaboratory through dialogue with our Instigator and Board of Advisors, quarterly meetings, annual reports, and other communications. The Instigator and other staff are excluded from the Board of Directors, to which they are responsible, but are charged with the planning and doing of our work. The Advisors’ charge is to give counsel as fitting. As we grow, we’ll also be enlarging our boards and staff as needed.</p>
                </div>
            </div>
        </div>

        <div class="info-block" id="directors-border-box">
            <div class="right-border-box">
                <div class="meet-item" id="board-of-directors">
                    <div class="section-subtitle" id="directors-title">
                        <h3>Board of Directors</h3>
                    </div>

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
                <div class="meet-item" id="adivsory-board">
                    <div class="section-subtitle">
                        <h3>Advisory Board</h3>
                    </div>
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
                <div class="meet-item" id="personnel">
                    <div class="section-subtitle">
                        <h3>Personnel</h3>
                    </div>
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

        <div class="info-block" id="more-to-come-border-box">
            <div class="right-border-box">
                <div class="do-page-section board" id="more-to-come">
                    <div id="more-to-come-copy">
                    <p>More to come soon...</p>
                    </div>
                    <div id="logo-meet">
                        <img src="../design/img/logo-draft.png " alt="curlicue-left">
                    </div>
                    <div id="meet-copyright">
                        <p>© David U.B. Liu 2023</p>
                    </div>
                </div>
            </div>
        </div>

    </div>
</body>