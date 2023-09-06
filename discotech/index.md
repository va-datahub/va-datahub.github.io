---
title: "Smallsat Resources"
layout: category

feature_row:
  - image_path: /assets/images/station.jpg
    title: "Virginia Ground Station Network"
    excerpt: "Read more on Virginia Tech's Ground Station Services. For more information contact Jonathan Black at Virginia Tech at jonathan.black@vt.edu"
    url: "/assets/content/VSDC_Ground_Station_Network_Services.pdf"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/smallsat3.png
    alt: "sat"
    title: "DISCOTech - Smallsat Mission Analysis Tool"
    excerpt: "DISCOTech is a modular and highly customizable Variable-Length Genetic Algorithm that interfaces with Model-Based Systems Engineering tools to solve complex engineering challenges."
    url: "/assets/content/VSDC_DISCOTech_Tool.pdf"
    btn_label: "Read more"
    btn_class: "btn--primary"
feature_row9:
  - image_path: /assets/images/galaxy.jpg 
    alt: "galaxy"
    title: "Journal of Spacecraft and Rockets Publication"
    excerpt: "Check out Virginia Tech's paper on Genetic-Algorithm-Based Design for Rideshare and Heterogeneous Constellations"
    url: /assets/content/WagnerJSR-1.a34527.pdf
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/images/astronomy.jpg
    alt: "astronomy"
    title: "American Astronomical Society"
    excerpt: "Read more on the Design of a Resilient Rideshare-Based Small Satellite Constellation Using a Genetic Algorithm"
    url: "/assets/content/AAS2019PaperFINAL.pdf"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row7:
  - image_path: /assets/images/smallsat6.jpg
    alt: "tree"
    title: "Smallsat Capabilities Inventory"
    excerpt: "Check out our list of Smallsat Capabilities Inventory"
    url: "/assets/content/VirginiaSmallsatLocations.pdf"
    btn_label: "Read more"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/wallops.jpeg
    alt: "tech"
    title: "Wallops Flight Facility Intergration and Testing Customer Handbook"
    excerpt: "NASA Wallops Integration and Test Capabilities"
    url: "/assets/content/Wallops IT Capabilities Handbook_updates_08.11.22_ (1).pdf"
    btn_label: "Read more"
    btn_class: "btn--primary"
feature_row8:
  - image_path: /assets/images/smallsat2.jpg
    resize: "512x720"
    alt: "tech"
    title: "Universal CubeSat Chassis for Experimenters"
    excerpt: "Ut ProSat-x BUS"
    url: "/assets/content/VSDC_Deliverable14_UPS1_Satellite Bus.pdf"
    btn_label: "Read more"
    btn_class: "btn--primary"    
---

<h3 style="text-align:center">Need help with designing and testing a Smallsat? </h3>
<p style="text-align:center">Check out the links below for several valuable resources.</p>
<br>
<hr>


{% include feature_row id="feature_row6" type="center" %}

<div class="row">
  {% for feature in site.feature_row9 %}
  <div class="col-md-6">
    <h2>{{ feature.title }}</h2>
    <img src="{{ feature.image_path }}" alt="{{ feature.image_alt }}" class="img-responsive">
    <p>{{ feature.excerpt }}</p>
  </div>
  {% endfor %}
</div>

{% include feature_row id="feature_row7" type="right" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row8" type="right" %}

<!--<h1 style="text-align:center"> Example Projects</h1>
<br>-->
{% include feature_row id="feature_row" type="left" %}