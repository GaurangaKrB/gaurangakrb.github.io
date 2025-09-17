---
layout: single
title: "Gallery"
collection: portfolio
permalink: /portfolio/gallery/
---

{% include base_path %}

<style>
  /* outer spacing */
  .gallery-timeline {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  /* date headings */
  .gallery-timeline h2 {
    margin-top: 3rem;
    font-size: 1.5rem;
    border-bottom: 2px solid #e0e0e0;
    padding-bottom: 0.5rem;
    color: currentColor;
  }

  /* grid wrapper */
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px,1fr));
    grid-gap: 1rem;
    margin-top: 1rem;
  }

  /* each image + caption */
  .gallery-grid figure {
    margin: 0;
    background: var(--color-canvas-subtle);
    border-radius: 4px;
    overflow: hidden;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
  .gallery-grid img {
    display: block;
    width: 100%;
    aspect-ratio: 1 / 1; /* Makes the image container square */
    object-fit: cover;   /* Makes the image fill the container without stretching */
  }
  .gallery-grid figcaption {
    padding: 0.5rem;
    font-size: 0.9rem;
    color: #222;
    text-align: center;
    background: rgba(255,255,255,0.85);
  }
  
  /* Dark‐mode override: dark background + light text */
  @media (prefers-color-scheme: dark) {
    .gallery-grid figcaption {
      background: rgba(0,0,0,0.7);
      color: #eee;
    }
  }
</style>

<div class="gallery-timeline">

  <h2>September - October, 2025</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/AIPM-1.JPG' | relative_url }}" alt="Event 404">
      <figcaption>With Prof. Elizabeth Stuart! (Johns Hopkins University) and Dr. Kannan Natarajan (Senior VP and Head, Global Data Sciences and Analytics, Pfizer, USA)</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/Workshop_ss.jpg' | relative_url }}" alt="Event 404">
      <figcaption>Conducted an 8 hour workshop in foundations of ML @ GLA, Mathura </figcaption>
    </figure>
    </div>

  <h2>June - August 2025</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/icts1_hd.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ ICTS with Prof. Ashoke Sen</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/icts2_hd.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ DSPOM-II, ICTS</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/icts3_hd.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ ICTS</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/with David Gross.jpg' | relative_url }}" alt="Event 404">
      <figcaption>Nobel Laureate, David Gross @ ICTS</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/icts4_hd.jpg' | relative_url }}" alt="Event 404">
      <figcaption>Nobel Laureate, David Gross @ ICTS</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/LAVA2025_1.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ LAVA, IIT-G</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/LAVA2025_2.JPG' | relative_url }}" alt="Event 404">
      <figcaption>@ LAVA, IIT-G</figcaption>
    </figure>
    </div>

  <h2>May - July 2024</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/profile.png' | relative_url }}" alt="Event 404">
      <figcaption>@ MIT</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/new york.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ New York (93rd floor)</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/harvard.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ Harvard Medical School</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/mit_.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ MIT</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/advik.jpg' | relative_url }}" alt="Event 404">
      <figcaption>with prodigy, Advik @ Brookline, MA</figcaption>
    </figure>
    </div>

  <h2>Oct 2023</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/inno.jpg' | relative_url }}" alt="Event 404">
      <figcaption>@ AAM-Ganitmela, Assam</figcaption>
    </figure>
  </div>

</div>
