---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Advisor

{% include list.html data="members" component="portrait" filters="role: prof" %}

## PhD students

{% include list.html data="members" component="portrait" filters="role: phd" %}

## Master students

{% include list.html data="members" component="portrait" filters="role: master" %}

## Undergraduate students

{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html background="images/background.jpg" dark=true %}

Come join us! We encourage all to apply.

{%
  include button.html
  type="link"
  text="Join us"
  link="05-join-us/"
%}

{% include section.html %}

## Alumnus

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
