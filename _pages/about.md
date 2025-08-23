---
permalink: /
title: "Welcome to My Website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<blockquote class="hero-quote">
  “The greater danger for most of us lies not in setting our aim too high  
  and falling short; but in setting our aim too low, and achieving our mark.”
  <footer>― Michelangelo Buonarroti</footer>
</blockquote>

<style>
  .hero-quote {
    max-width: 600px;              /* narrower for readability */
    margin: 3rem auto;               /* vertical space + centered */
    padding-left: 1rem;              /* space for the border */
    font-size: 1.8rem;               /* large but not overwhelming */
    line-height: 1.4;                /* comfortable linespacing */
    font-style: italic;              /* keeps the “quote” feel */
    color: currentColor;             /* adapts to light/dark mode */
    border-left: 4px solid #007acc;  /* accent color on the left */
  }

  .hero-quote footer {
    margin-top: 1rem;
    font-size: 1rem;                 /* smaller author line */
    font-style: normal;              /* remove italic for credit */
    font-weight: 500;
    color: currentColor;
    opacity: 0.75;                   /* a bit muted */
    text-align: left;                /* align to the main text */
  }

  /* Responsive down-scale on mobile */
  @media (max-width: 600px) {
    .hero-quote {
      font-size: 1.4rem;
      margin: 2rem auto;
    }
    .hero-quote footer {
      font-size: 0.9rem;
    }
  }
</style>


I am a researcher in AI and ML. My primary research areas include Causal AI, RL, and Gen AI. Additionally, I apply ML methodologies to interdisciplinary problems across Computational Biology, Public Health, and Computational Linguistics (e.g., Psychology).

I transitioned from the graduate program in Mathematics at IIT Kharagpur to complete my Master’s degree in Data Science at the Chennai Mathematical Institute (CMI), graduating in 2025. In 2024, I was honored to receive the [Khorana Scholarship](https://iusstf.org/khorana-program-for-scholars) to spend my summer at Harvard Medical School under the mentorship of [Prof. Yu-Hua Tseng](https://yhtsenglab.org/).

Outside my professional pursuits, I cherish diverse intellectual and recreational activities: cinematic arts (especially dramatic narratives), Chess, puzzle-solving, competitive programming, travel, photography, sketching, and writing philosophical and biographical articles. You can explore more of my thoughts and experiences in the [blogs](https://gaurangakrb.github.io/year-archive/) section.

I am always eager to connect, exchange ideas, and collaborate. Please feel free to reach out through any of my social media platforms.

<style>
  :root {
    --timeline-line-color: #e0e0e0;
    --timeline-dot-color: #007acc;
    --timeline-dot-border-color: #ffffff; /* Use a light color for dark mode compatibility */
    --timeline-text-color: #555;
    --timeline-date-color: #777;
    --timeline-link-color: #007acc;
  }

  /* Adjust colors for dark mode if your site has one */
  [data-theme="dark"] {
    --timeline-line-color: #444;
    --timeline-dot-border-color: #252a34; /* Match dark background */
    --timeline-text-color: #ccc;
    --timeline-date-color: #999;
  }

  .timeline {
    list-style: none;
    padding: 0;
    margin: 3rem 0;
    position: relative;
    padding-left: 30px; /* Space for the timeline line and dots */
  }

  /* The vertical timeline bar */
  .timeline::before {
    content: '';
    position: absolute;
    top: 5px;
    bottom: 5px;
    left: 8px; /* Centered with the dot */
    width: 2px;
    background: var(--timeline-line-color);
  }

  .timeline-item {
    position: relative;
    margin-bottom: 2.5rem; /* Space between items */
  }
  .timeline-item:last-child {
      margin-bottom: 0;
  }

  /* The dot on the timeline */
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -25px; /* (30px padding - dot width/2) to position on the line */
    top: 5px;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background-color: var(--timeline-dot-color);
    border: 3px solid var(--timeline-dot-border-color);
    z-index: 1;
  }

  .timeline-date {
    display: block;
    font-size: 0.9rem;
    font-weight: 600;
    color: var(--timeline-date-color);
    margin-bottom: 0.5rem;
  }

  .timeline-content p {
    margin: 0;
    font-size: 1rem;
    line-height: 1.6;
    color: var(--timeline-text-color);
  }
  
  .timeline-content a {
    font-weight: 600;
    color: var(--timeline-link-color);
    text-decoration: none;
    transition: all 0.2s ease-in-out;
  }

  .timeline-content a:hover {
    text-decoration: underline;
    filter: brightness(1.1);
  }

  /* Responsive adjustments */
  @media (max-width: 600px) {
    .timeline {
      padding-left: 25px;
      margin: 2rem 0;
    }
    .timeline-item::before {
      left: -22px;
    }
  }
</style>

## Latest News

<ul class="timeline">
  <li class="timeline-item">
    <time datetime="2025-08-15" class="timeline-date">Aug 15, 2025</time>
    <div class="timeline-content">
      <p>Started working on two projects led by Amitava Das: neural genomics (<a href="https://pragyaai.github.io/ndna/" target="_blank" rel="noopener">project page</a>) and spatial reasoning in 3D.</p>
    </div>
  </li>

  <li class="timeline-item">
    <time datetime="2025-08-15" class="timeline-date">Aug 15, 2025</time>
    <div class="timeline-content">
      <p>Participated in <a href="https://www.icts.res.in/program/DSPOM" target="_blank" rel="noopener">Data Science: Probabilistic and Optimization Methods II</a> at the International Centre for Theoretical Sciences (ICTS).</p>
    </div>
  </li>

  <li class="timeline-item">
    <time datetime="2025-07-07" class="timeline-date">Jul 07, 2025</time>
    <div class="timeline-content">
      <p>Graduated from CMI with an M.Sc. in Data Science.</p>
    </div>
  </li>

  <li class="timeline-item">
    <time datetime="2025-07-07" class="timeline-date">Jul 07, 2025</time>
    <div class="timeline-content">
      <p>Participated in <a href="https://mmlabiitg.github.io/lava2025/" target="_blank" rel="noopener">LAVA 2025</a> — an 8-day Summer School on AI & ML for Computer Vision and Language Modelling.</p>
    </div>
  </li>

  <li class="timeline-item">
    <time datetime="2025-06-08" class="timeline-date">Jun 08, 2025</time>
    <div class="timeline-content">
      <p>Will be joining IISc–TCS Innovation Labs!</p>
    </div>
  </li>

  <li class="timeline-item">
    <time datetime="2025-04-05" class="timeline-date">Apr 05, 2025</time>
    <div class="timeline-content">
      <p>Appeared for the last exam of my Master’s degree at CMI.</p>
    </div>
  </li>
</ul>
