---
layout: default
title: Research Topic
---

<h1 style="text-align: center; margin-bottom: 70px;">Research Topics</h1>
<div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; padding: 0px;">
    <a href="/research_topic1" style="position: relative; margin: 0 40px;">
      <img src="assets/images/Airfoil_Brain.jpg" alt="Figure 1" class="blur-image" style="border-radius: 1%; width: 100%; max-width: 500px; height: auto; display: block; margin-bottom: 40px;"/>
      <div class="overlay">Framework Development</div>
    </a>
    <a href="/research_topic2" style="position: relative; margin: 0 40px;">
      <img src="assets/images/ROM.jpg" alt="Figure 2" class="blur-image" style="border-radius: 1%; width: 100%; max-width: 500px; height: auto; display: block; margin-bottom: 40px;"/>
      <div class="overlay">Data-driven ROM</div>
    </a>
</div>
<div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; padding: 0px;">
    <a href="/research_topic3" style="position: relative; margin: 0 40px;">
      <img src="assets/images/aircraft_design.jpg" alt="Figure 3" class="blur-image" style="border-radius: 1%; width: 100%; max-width: 500px; height: auto; display: block; margin-bottom: 40px;"/>
      <div class="overlay">ML/AL for Aerodynamic Design</div>
    </a>
    <a href="/research_topic4" style="position: relative; margin: 0 40px;">
      <img src="assets/images/data_processing.jpg" alt="Figure 4" class="blur-image" style="border-radius: 1%; width: 100%; max-width: 500px; height: auto; display: block; margin-bottom: 40px;"/>
      <div class="overlay">Experimental Data Processing</div>
    </a>
</div>

<style>
    .blur-image {
      filter: blur(5px); /* Apply blur by default */
      transition: filter 0.5s ease; /* Smooth transition for the blur effect */
    }

    .overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      width: 90%;
      transform: translate(-50%, -50%);
      color: #201919; /* Text color */
      font-size: 28px; /* Font size */
      font-weight: bold;
      opacity: 1; /* Start with the text visible */
      text-align: center; /* Center text within the overlay */
      display: flex; /* Use flexbox to center content */
      justify-content: center; /* Center horizontally */
      align-items: center; /* Center vertically */
      transition: opacity 0.5s ease;
      pointer-events: none;
    }
  
    a:hover .blur-image {
      filter: none; /* Remove blur on hover */
    }
  
    a:hover .overlay {
      opacity: 0; /* Fade out text on hover */
    }
</style>