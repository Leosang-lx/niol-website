---
---

# NIO Lab Website

**NIOL** is the abbreviation of **Network Intelligence and Optimization Lab**, relying on Southern University of Science and Technology (SUSTech), researches mainly focus on mobile edge computing, distributed learning and
inference, network optimization and economics.

![our_image](images/photo.jpg)


{% 
  include section.html
  background="images/background.jpg"
  dark=false
%}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{%
include button.html
type="email"
text="niol_sustech@163.com"
link="niol_sustech@163.com"
%}
{%
include button.html
type="email"
text="tangm3@sustech.edu.cn"
link="tangm3@sustech.edu.cn"
%}
{%
include button.html
type="address"
tooltip="Our location on Google Maps for easy navigation"
text="Room 646A, Southern Tower of CoE"
link="https://www.google.com/maps"
%}
