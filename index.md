---
title: Home
layout: page
gallery: true
---

<br>

{% include gallery-figure.html img="opti_logo.png" alt="Opticolumn logo of a lighthouse on top of a book with the sea in the distance." width="50%" %}

<br>

# Overview

<br>

The Opticolumn Tool Kit are a series of scripts developed to embed more accurate Optical Character Recognition (OCR) into wide variety of archival documents.

<br>

**My goals in developing this OCR kit continue to be:**

- Implementing free, open-source models for sustainability.
- Ensuring these models don't require an API login or tokens, and run locally after their initial download, for data privacy.
- Achieving a significant improvement in the accuracy of both typed and handwritten text materials.
- Keeping file size growth relatively minimal (5–15 percent) with the addition of the OCR layer.
- Ensuring that processed files meet the WCAG definition of "programmatic text".
- Avoiding all text recognition models that have demonstrated a vulnerability to hallucination.	
- Making the tool freely available to other institutions facing similar challenges.

<br>

__Opticolumn Tool Kit Resources and Applications__

- [Opticolumn](https://github.com/Scholarly-Projects/opticolumn)
    - Intended for archival scans and designed for type, handwritten text, cursive or a combination of all three. The tool can handle unorthodox arrangements of text, such as annotations and marginalia, but reading order arrangement is not as developed as the following script.
- [Opticolumns](https://github.com/Scholarly-Projects/opticolumns)
    - Intended for archival scans of large scale multi-columned materials, such as newspapers. 
- [Opticolumn_Editor](https://github.com/Scholarly-Projects/opticolumn_editor)
    - Intended to create OCR using Opticolumn that produces a CSV of the OCR file that can be edited and processed gain to incorporate copy edits into the final embedded layer. This method is recommended if you need to produce OCR that surpasses the 85-95% accuracy benchmarks of Opticolumn and Opticolumns.
- _Forthcoming_:
    - Optical Music Recognition tool, to make the library's International Jazz Collection and digitized sheet music fully accessible.

<br>

_Step-by-step instructions for installation and running these scripts are included in each tool's setup.md file._

<br>

## About the Project

<br>

* [Article published by _Collections: A Journal for Museum and Archives Professionals_, June 2026](https://journals.sagepub.com/doi/full/10.1177/15501906261439241){:target="_blank" rel="noopener"}

* [OSF Repository for Post-Processing OCR Accuracy Survey](https://osf.io/9f483/overview){:target="_blank" rel="noopener"}

* [Presentation Site for Fall 2026 Renfrew Colloquium on the Project](https://aweymo-ui.github.io/practices-rc/){:target="_blank" rel="noopener"}

* [Slide Deck for the Presentation](https://indd.adobe.com/view/a5ed9089-f1ec-4962-905a-75fb99c9f259){:target="_blank" rel="noopener"}

* [Presentation Recording](https://www.youtube.com/watch?v=8a54gpxjTPE)

<br>

## Background

<br>

The Opticolumn tool kit was developed for overhauling the [University of Idaho Library's](https://www.lib.uidaho.edu/) [digital collections](https://www.lib.uidaho.edu/digital/), to make the collection more discoverable and accessible. The development of the original [Opticolumn](https://github.com/Scholarly-Projects/opticolumn) tool is written about in greater detail in [_Transparent Practices: OCR and AI in the Archives_](https://journals.sagepub.com/doi/full/10.1177/15501906261439241), by Rebecca Hastings and Andrew Weymouth. _Collections: A Journal for Archives and Museum Professions_, June 2026.

<br>

_Andrew Weymouth, Fall 2026._

<br>

------

{% include template/credits.html %}

{% include feature/image.html objectid="demo_001" %}
