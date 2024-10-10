---
title: Publications
nav:
  order: 4
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="link"
  text="International Conferences"
  link="03-publications/#international-conferences"
%}

{%
  include button.html
  type="link"
  text="International Journals"
  link="03-publications/#international-journals"
%}


{% include section.html %}

## Highlighted

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## International Conferences

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" filters="type: paper" %}

{% include section.html %}

## International Journals

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" filters="type: journal" %}
