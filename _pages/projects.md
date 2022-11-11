---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
order: 2
---
##### **Fast Calculation of Effective Number of Cosmological Neutrinos in Comoving Variables**
*Jun. 2022 - Present* 

*INSTITUTE NAZIONALE DE FISICA NUCLEARE - SEZIONE DI TORINO, PI: DR. STEFANO GARIAZZO*

• Numerically computing number of effective relativistic neutrino species in comoving variables after non-instantaneous neutrino decoupling.
• Developing a fast code with 10e-2 accuracy to the full calculations, but reducing computation time from days to a few seconds.
• Considering effects of neutrino oscillations, electron mass suppression, finite temperature QED corrections, etc. on the N􀕊􀕋􀕋 .
• Calculating in a model-independent manner to analyze the impact of stellar neutrino species, WIMPs, thermal dark matter, etc.

---
##### **Astronomical data-processing pipeline creation for the Devasthal Fast Optical Telescope**
*May. 2022* 

*ARYABHATTA RESEARCH INSTITUTE OF OBSERVATIONAL SCIENCES (ARIES OBSERVATORY, NAINITAL)*

• Created an open online data archive for wide-field photometry observations from DFOT.
• An automated computational pipeline was developed to convert raw FITS astronomical data from each observation to processed images.
• Pre-processing, astrometry and photometry was done using Python (Astropy, Photoutils, Astroalign, CCDProc) to make the process easily modifiable
for monitoring of transients, variability of stars, AGNs, etc.

---
##### **Thermalization of Neutrinos in the Early Universe (Master’s thesis)**
*Jan. 2022 - May. 2022* 

*INSTITUTE NAZIONALE DE FISICA NUCLEARE - SEZIONE DI TORINO, PI: DR. STEFANO GARIAZZO*

• Understood neutrino decoupling in standard cosmology in both instantaneous and non-instantaneous case.
• Solved the relativistic Boltzmann equations in comoving variables to see effects on photon and neutrino temperature evolution.
• Calculated distortions in the neutrino distributions due to electron-positron annihilation by computing the collision terms for each interaction.

---
##### **Study on the Modern Cosmological Model (Bachelor’s Thesis)**
*Aug. 2021 - Dec. 2021* 

*INSTITUTE NAZIONALE DE FISICA NUCLEARE - SEZIONE DI TORINO, PI: DR. STEFANO GARIAZZO*

• Understood geometry of curved spacetime, Equivalence principle, Einstein and Friedmann equations in Lambda-CDM model.
• Studied statistical mechanics, thermodynamics and the dynamics of an expanding universe, and constructed the Boltzmann equations.
• Studied dynamics of the early universe, including inflation, species decoupling and transitions of epochs.

---

##### **Study on Weak Interactions and Neutrinos**
*Jan. 2021 - May. 2021* 

*NUCLEAR AND PARTICLE PHYSICS GROUP, DEPT. OF PHYSICS, BITS PILANI, PI: PROF. RISHIKESH VAIDYA*

• Understood weak gauge interactions and the family structure of leptons to appreciate masslessness of neutrinos within the standard model.
• Understood the experimental background, solar and atmospheric neutrino anomalies as well as accelerator experiments.
• Understood the Dirac and Majorana nature of neutrinos and Neutrino oscillations as a solution to these problems.

---

##### **Experimental and Computational Analysis of Droplet Dynamics on Superhydrophobic Surfaces*

*Aug. 2020 - May. 2021* 

• Setup and conducted the experiment using a high-speed camera for water droplets impacting syperhydrophobic acrylic surfaces.
• Developed computational fluid dynamic simulations for varying multiphase cases and compared with the experimental data.

---

##### **Optimization of Large Rotating Plug of Prototype Fast Breeder Reactor (PFBR, Kalpakkam)**
*INDIRA GANDHI CENTRE FOR ATOMIC RESEARCH (IGCAR), PI: MR. S.R. AITHAL*

*May. 2019 - Jul. 2019*

• Optimized components of the top shield of the new 500MWe fast breeder nuclear reactor being constructed in Kalpakkam, Tamil Nadu.
• Designed Large Diameter Bearings to handle the extreme temperature gradient in the top shield using spacer balls for high reliability.

---

##### **Image Sensing by Hypersprectal Camera and Sun-Sensor Optimization on Nanosatellite*

*May - July 2020*

• Worked in the Payload subsystem on image sensing through a hyperspectral camera to detect algal bloom patterns in the Indian Ocean
• Worked in Attitude Determination and Control subsystem (ADCS) on Sun Sensors Placement and Optimization for the nanosatellite.

---


<!--
<div class="projects grid">

  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>
-->


