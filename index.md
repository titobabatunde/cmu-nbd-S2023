---
title: Home
---

# CMU National Biomechanics Day 2023

Welcome to National Biomechanics Day at CMU! Register for the event [here](https://github.com/greenelab/lab-website-template). This is a two-day event held virtually on March 26th and in-person at CMU on April 2nd. We aim to introduce Biomechanics to high school students and teachers. Learn about impacts of climate change on [animal biomechanics](https://www.greenelab.com/), [3D printed prostheses](https://www.greenelab.com/), design your own [structure made out of DNA](https://www.greenelab.com/), and [more](https://www.greenelab.com/)!


{%
  include link.html
  type="search"
  icon=""
  text="Check out CMU NBD 2021"
  link="https://cmubiomechday.wordpress.com/2021-homepage/"
  style="button"
%}
{%
  include link.html
  type="search"
  icon=""
  text="Check out CMU NBD 2022"
  link="https://cmubiomechday.wordpress.com/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/cmu-banner-2.png" %}

{% include section.html %}

# Highlights

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="sessions/3d-printing-legs"
  title="3D Printing Legs"
  icon="fa-solid fa-print"
  flip=true
  text=text
%}

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
