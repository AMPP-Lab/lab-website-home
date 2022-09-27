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

<div class="orbit" role="region" aria-label="Lab Pictures" data-orbit>
  <div class="orbit-wrapper">
    <div class="orbit-controls">
      <button class="orbit-previous"><span class="show-for-sr">Previous Slide</span>&#9664;&#xFE0E;</button>
      <button class="orbit-next"><span class="show-for-sr">Next Slide</span>&#9654;&#xFE0E;</button>
    </div>
    <ul class="orbit-container">
      <li class="is-active orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="/lab-website-home/assets/img/lab_photo_1.jpg" alt="Space">
          <figcaption class="orbit-caption">L to R: Elizabeth Bell, Caroline Lee, Mike Chmielewski, Alexa Jimenez, Mayson Trujillo.</figcaption>
        </figure>
      </li>
      <li class="orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="/lab-website-home/assets/img/lab_photo_2.jpg" alt="Space">
          <figcaption class="orbit-caption">The AMPP Lab STAR! </figcaption>
        </figure>
      </li>
    </ul>
  </div>
  <nav class="orbit-bullets">
    <button class="is-active" data-slide="0">
      <span class="show-for-sr">First slide details.</span>
      <span class="show-for-sr" data-slide-active-label>Current Slide</span>
    </button>
    <button data-slide="1"><span class="show-for-sr">Second slide details.</span></button>
  </nav>
</div>

## Research Overview
Research in the AMPP (Assessment, Measurement, Personality, & Psychopathology) lab focuses  on measurement and assessment, structural models of psychopathology, and the validity of conceptualizations of clinical/health/personality constructs.  We believe that improved measurement and accurate representations of psychopathology and other psychologically relevant constructs, along with open science practices and ensuring high quality data, are essential for the continued advancement of clinical science.  We also investigate associations of “normal” personality traits and other individual differences with psychopathology and clinically relevant constructs.  Finally, our lab has a strong commitment to diversity and inclusion.     
