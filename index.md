---
---

# Welcome to the LIMB Lab!

The Locomotion and Imaging for Musculoskeletal Biomechanics (LIMB) Lab is located at the University of Calgary's McCaig Institute, run by Dr. Koren Roach. Our research involves investigating how joint biomechanics, physical activity, and kinematics contribute to the onset and progression of musculoskeletal diseases such as osteoarthritis.

A key proponent of the LIMB Laboratory is our state-of-the-art biplanar videoradiography (BVR) system, consisting of two high-speed video camera, two image intensifiers, and two X-ray sources. BVR allows for a precise assessment of three-dimensional bone motion, enabling assessment of dynamic changes in joint function. 

{% include section.html %}

## Mission Statement

The LIMB Lab studies how joints move, and what changes following injury or disease. Using high-speed biplane videoradiography, multi-modal imaging assessments, and motion analysis, we measure joint biomechanics in fine detail to understand how osteoarthritis and other musculoskeletal conditions begin and progress, so we can improve prevention, treatment, and quality of life.

{% include section.html %}

## Lab Values

<div class="lab-values">
  <div class="value-card">
    <h3>Respect & Inclusion</h3>
    <p>We value the perspectives and expertise of all lab members and we create an environment where all individuals feel valued and empowered to contribute.</p>
  </div>

  <div class="value-card">
    <h3>Teamwork & Collaboration</h3>
    <p>We draw on our backgrounds in engineering, kinesiology, and biomedical sciences to collaborate across disciplines within and beyond our lab. </p>
  </div>

  <div class="value-card">
    <h3>Integrity & Honesty</h3>
    <p>We uphold the highest standards of ethical conduct and are honest and transparent in our research and with one another.</p>
  </div>

  <div class="value-card">
    <h3>Rigour & Precision</h3>
    <p>We approach every question with sound methodology, paying careful attention to detail from data collection through analysis. </p>
  </div>

  <div class="value-card">
    <h3>Drive & Dedication</h3>
    <p>We bring energy and focus to our work and shared goals, persist through setbacks, and support each other through the long arc of research. </p>
  </div>

  <div class="value-card">
    <h3>Fun & Curiosity</h3>
    <p>We ask bold questions, find joy in discovery, stay open to surprises in our data, and believe good science and a good time go hand in hand.</p>
  </div>
</div>

<style>
.lab-values {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
  margin: 2rem 0;
}

.value-card {
  background: #fff4e6;
  border-radius: 16px;
  padding: 1.5rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  text-align: center;
}

.value-card h3 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  color: #D6001C;
}

.value-card p {
  margin-bottom: 0;
  font-size: 0.95rem;
}

@media (max-width: 768px) {
  .lab-values {
    grid-template-columns: 1fr;
  }
}
</style>

{% include section.html %}

## Highlights

{% capture text %}

Our research focuses on using advanced medical imaging to better understand joint biomechanics.

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
  image="images/research_photos/DF_ankle.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We are always looking for passionate and enthusiatic post-doctoral fellows, graduate students (MSc and PhD), and undergraduate students to join our lab. If you are interested in joining our team or would like to learn more send us an email.

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/logos/LIMB_Logo_Full.jpg"
  link="contact"
  title="Reach out"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are comprised of people with backgrounds in health sciences, kinesiology, and engineering. Learn more about our current lab members.

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
  image="images/team_photos/Lab_Photo.jpg"
  link="team"
  title="Our Team"
  text= text
%}
