---
layout: page
permalink: /hobbies/
title: Hobbies
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
    justify-content: space-between; /* Distribute tiles evenly */
    margin-top: 20px;
  }

  /* Individual tile */
  .tile {
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    width: calc(33.33% - 20px); /* Adjust width to 1/3 minus the gap */
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

  @media (max-width: 1200px) {
    .tile {
      width: calc(50% - 20px); /* Two tiles per row */
    }
  }

  @media (max-width: 600px) {
    .tile {
      width: 100%; /* One tile per row */
    }
  }
</style>


<div class="tiles-container">
  <div class="tile">
    <h2>One Week Cycling in France</h2>
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

<!-- ## 2021 Adventures -->

<!-- <div class="tiles-container"> -->
  <div class="tile">
    <h2>Hike and fly</h2>
    <p>
      After getting the paragliding license, I had some beautiful Hike & Fly experiences!
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="11171987616" data-style="standard"></div>
    <script src="https://strava-embeds.com/embed.js"></script>
  </div>

  <div class="tile">
    <h2>Running</h2>
    <p>
      Finally took part in a race and improve my time for half-marathon!  
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="12637074023" data-style="standard"></div><script src="https://strava-embeds.com/embed.js"></script>
  </div>

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

  <div class="tile">
    <h2>Cylcing in Switzerland</h2>
    <p>
      I like to climb mountain passes in Switzerland, here for example a tour over the famous Gotthard pass.
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="7441558065" data-style="standard"></div><script src="https://strava-embeds.com/embed.js"></script>
  </div> 

  <div class="tile">
    <h2>Hiking in Switzerland</h2>
    <p>
      Probably one of the most stunning hikes that exist, and at the same time my longest
    </p>
    <div class="strava-embed-placeholder" data-embed-type="activity" data-embed-id="7601623584" data-style="standard"></div><script src="https://strava-embeds.com/embed.js"></script>
  </div>

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
