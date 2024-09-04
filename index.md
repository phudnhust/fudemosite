---
title: Home
---

# DemoSiteLab - National ABC University

DemoSiteLab was formed on the 1 August 2018, with a research focus on computer vision and deep learning. It is now a group with three faculty members and more than 40 members including research fellows, research assistants, research engineers and PhD students.

Members in DemoSiteLab conduct research primarily in low-level vision, image and video understanding, and generative AI. Have a look at the overview of our research. All publications are listed here.

We are always looking for motivated PhD students, postdocs, research assistants who have the same interests like us. Check out the careers page and follow us on Twitter.

{% include section.html %}

## Highlights

<!--- Part "Our research" -->

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

<!--- Part "Browse our projects" --> 

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

<!--- Part "Meet our team" --> 

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
