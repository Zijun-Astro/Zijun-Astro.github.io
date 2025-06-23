---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
**West High School**								Madison, WI
                                    from 2022-Present

Research Interests:
======
Astrophysics, Exoplanetary Science
  
Research Experience:
======
* **(September 2024 - Present) Research Assistant, Department of Astronomy, UW-Madison:**
  * Performed a TTV Analysis & and confirmation for the TOI-1937Ab system utilizing data from Andrew Vanderburg.
  * Published with Alyssa Jankowski as the 5th author on a research paper in PASP.
  * Working on the TOI-1130 System to confirm the planetary characteristics of [Korth et al. 2023](https://ui.adsabs.harvard.edu/abs/2023A&A...675A.115K) using new TESS Data.
 
* **(May 2025 - December 2025) NASA STEM Enhancement in Earth Science (SEES):**
  * Accepted for the NASA SEES 2025 Cohort.
  * Utilizing HOPS, AstroImageJ, Stellarium, nd Markov-Chain-Monte-Carlo to analyze data from SARA and TESS.
  * Presenting the analysis at the American Geophysical Union Fall Conference.
 
* **Harvard Spatial Data Lab Intern:**
  * Intern at the Harvard Spatial Data Lab
  * Developed a light pollution analysis method using Prophet, a time series forecasting tool.
  * Presented Research through the 2025 Harvard CGA Conference.
  
* **(June 2024 - August 2024) Hubert Mack Thaxton Fellowship Intern, Department of Astronomy UW-Madison:**
  * Performed a mass constraint and TTV Analysis of the TOI-4468 system.
  * Utilized a Markov-Chain-Monte-Carlo fitting algorithm on both Radial Velocity Data and TESS Data.


* **NASA Student Launch (September 2024 - Present):**
  * Data Analysis Lead and Hardware Engineer for the Madison West Rocket Club NASA Student Launch Team.
  * Worked on developing the Data Analysis Procedure to determine the effectiveness of baffle designs
  * Collaborated with the NASA SL team to build the design the payload.
  * Team was awarded the [SLI Payload Design Award](https://www.nasa.gov/learning-resources/nasa-student-launch/current-teams/)
    
* **(June 2023 - December 2023) AGU Bright STaRs Research Internship:**
  * High School Research Presenter at the American Geophysical Union through the Bright STaRs Research Session.
  * Presented on extrapolation methodologies of three-dimensional general circulation models using ROCKE-3D data.
  * Explained the benefits of the Multi-Component Linear Regression Methodology versus the standard Gregory Method.


Publications
======
  <ul>{% for post in site.publications reversed %}
  {% unless post.cv_display == false %}
    {% include archive-single-cv.html %}
  {% endunless %}
{% endfor %}
</ul>
  
Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
