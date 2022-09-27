---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: ampp_header2.png
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true

---

<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 2</div>
      <img src="/lab-website-home/assets/img/lab_photo_1.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 2</div>
      <img src="/lab-website-home/assets/img/lab_photo_2.jpg" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="/lab-website-home/assets/img/lab_photo_1.jpg" style="width:100%" onclick="currentSlide(1)" alt="L to R: Elizabeth Bell, Caroline Lee, Mike Chmielewski, Alexa Jimenez, Mayson Trujillo">
    </div>
    <div class="column"> 
      <img class="demo cursor" src="/lab-website-home/assets/img/lab_photo_2.jpg" style="width:100%" onclick="currentSlide(2)" alt="AMPP Lab STAR">
    </div>
  </div>
</div>

## Research Overview
Research in the AMPP (Assessment, Measurement, Personality, & Psychopathology) lab focuses  on measurement and assessment, structural models of psychopathology, and the validity of conceptualizations of clinical/health/personality constructs.  We believe that improved measurement and accurate representations of psychopathology and other psychologically relevant constructs, along with open science practices and ensuring high quality data, are essential for the continued advancement of clinical science.  We also investigate associations of “normal” personality traits and other individual differences with psychopathology and clinically relevant constructs.  Finally, our lab has a strong commitment to diversity and inclusion.     
