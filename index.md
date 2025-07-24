---
---

# Welcome to the LIMB Lab!

The Locomotion, Imaging, Musculoskeletal and Biomechanics Lab is run by Dr. Koren Roach. Our research involves investigating how joint biomechanics, physical activity, and kinematics contribute to the onset and progression of musculoskeletal diseases such as osteoarthritis.
A key proponent of Dr. Roach's lab is the state-of-the-art dual fluoroscopy lab within McCaig Institute. Dual fluoroscopy is an X-ray based imaging system that is used to derive dynamic bony translations and rotations. The system consists of two high-speed video camera, two image intensifiers, and two X-ray sources. (Think of it like an X-ray video system :) )
Dual fluoroscopy (DF) is an X-ray based non-invasive imaging system that can derive dynamic bony translations and rotations. The system consists of two high-speed video cameras, two image intensifiers, and two X-ray sources.

{% include section.html %}

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
