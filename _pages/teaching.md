---
layout: page
permalink: /hobbies/
title: hobbies
description: I love to do outdoor sports and to travel. Here are some pointers to my favourite trips
nav: true
nav_order: 6
---

<style>
  /* Container for all tiles */
  .tiles-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: flex-start; /* Align tiles to the left */
    margin-top: 20px;
  }

  /* Individual tile */
  .tile {
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    width: 300px; /* Maintained width */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .tile:hover {
    transform: scale(1.05);
  }

  /* Larger text for headings */
  .tile h2 {
    font-size: 1.5em;
    margin-bottom: 10px;
    text-align: center;
  }

  /* Description text */
  .tile p {
    font-size: 1.1em;
    text-align: center;
    margin-bottom: 15px;
  }

  /* Strava embed responsiveness */
  .strava-embed-placeholder {
    width: 100%;
    height: auto;
    margin-bottom: 10px;
  }

  /* Image styling within tiles */
  .tile img {
    max-width: 100%;
    border-radius: 8px;
    margin-bottom: 10px;
  }

  /* Responsive adjustments */
  @media (max-width: 1600px) {
    .tile {
      width: 300px; /* Keep tile width consistent */
    }
  }

  @media (max-width: 1200px) {
    .tile {
      width: 300px; /* Maintain width to allow more tiles per row */
    }
  }

  @media (max-width: 992px) {
    .tile {
      width: 300px; /* Maintain width for consistency */
    }
  }

  @media (max-width: 600px) {
    .tile {
      width: 100%; /* Single tile per row on small screens */
    }
  }
</style>


<div class="tiles-container">
  <div class="tile">
    <h2>One Week Biking in France</h2>
    <p>From Geneva to Andorra (2024)</p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="12421702771" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>

  <div class="tile">
    <h2>One Week Hiking in the Pyrenees</h2>
    <p>From Andorra to Perpignan (2024)</p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="12500855830" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>
  <!-- <div class="tile">
    <h2>One Week Biking Through France</h2>
    <p>Followed by one week hiking through the Pyrenees.</p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="12426409737" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>

  <!-- <div class="tile">
    <h2>One Week Biking Through France</h2>
    <p>Followed by one week hiking through the Pyrenees.</p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="12453745686" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div> --> -->
<!-- </div> -->

<!-- ## 2021 Adventures -->

<!-- <div class="tiles-container"> -->
  <div class="tile">
    <h2>3 weeks Scandinavia - Galdhoppigen</h2>
    <p>
      Traveled by interrail, car, ship, and bus, from Zurich through Norway to the North Cape and back through Finland (2023)
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="9323049879" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>

  <div class="tile">
    <h2>3 weeks Scandinavia - Lofoten</h2>
    <p>
      Traveled by interrail, car, ship, and bus, from Zurich through Norway to the North Cape and back through Finland (2023)
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="9346909659" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>

  <!-- <div class="tile">
    <h2>Three Weeks Through Norway</h2>
    <p>
      Traveled by interrail, car, ship, and bus, from Zurich through Norway to the North Cape and back through Finland.
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="9303859549" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div> -->

  <!-- <div class="tile">
    <h2>Three Weeks Through Norway</h2>
    <p>
      Traveled by interrail, car, ship, and bus, from Zurich through Norway to the North Cape and back through Finland.
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="9310214478" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>
</div> -->

<!-- ## 2019 Adventures -->

<!-- <div class="tiles-container"> -->
  <div class="tile">
    <h2>3-Weeks US Roadtrip</h2>
    <p>
      We did a <a href="https://jannisborn.github.io/us-roadtrip/" target="_blank">3-weeks roadtrip</a> in the US, including 9 national parks.
    </p>
    <!-- Added Image -->
    {% include figure.liquid loading="eager" path="assets/img/us_roadtrip.JPG" title="Screenshot" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
