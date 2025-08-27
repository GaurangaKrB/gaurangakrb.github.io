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
    max-width: 600px;
    margin: 3rem auto;
    padding-left: 1rem;
    font-size: 1.8rem;
    line-height: 1.4;
    font-style: italic;
    color: currentColor;
    border-left: 4px solid #007acc;
  }

  .hero-quote footer {
    margin-top: 1rem;
    font-size: 1rem;
    font-style: normal;
    font-weight: 500;
    color: currentColor;
    opacity: 0.75;
    text-align: left;
  }

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
    --timeline-bg: #f9f9f9;
    --timeline-line-color: #ddd;
    --timeline-dot-color: #007acc;
    --timeline-card-bg: #ffffff;
    --timeline-card-shadow: rgba(0, 0, 0, 0.08);
    --timeline-text-color: #333;
    --timeline-date-color: #777;
    --timeline-link-color: #007acc;
  }

  /* Adjust colors for dark mode if your site has one */
  [data-theme="dark"] {
    --timeline-bg: #1e1e1e;
    --timeline-line-color: #444;
    --timeline-card-bg: #2d2d2d;
    --timeline-card-shadow: rgba(0, 0, 0, 0.2);
    --timeline-text-color: #ccc;
    --timeline-date-color: #999;
  }

  /* The main timeline container */
  .timeline {
    position: relative;
    max-width: 900px;
    margin: 4rem auto;
    padding: 0;
    list-style: none;
  }

  /* The central timeline bar */
  .timeline::before {
    content: '';
    position: absolute;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 3px;
    height: 100%;
    background-color: var(--timeline-line-color);
    border-radius: 3px;
  }
  
  /* Each item in the timeline */
  .timeline-item {
    padding: 1rem 3rem;
    position: relative;
    width: 50%;
    opacity: 0; /* Initially hidden for animation */
    animation: slideInUp 0.6s ease-out forwards;
  }
  
  /* Stagger the animation for each item */
  .timeline-item:nth-child(1) { animation-delay: 0.1s; }
  .timeline-item:nth-child(2) { animation-delay: 0.2s; }
  .timeline-item:nth-child(3) { animation-delay: 0.3s; }
  .timeline-item:nth-child(4) { animation-delay: 0.4s; }
  .timeline-item:nth-child(5) { animation-delay: 0.5s; }
  .timeline-item:nth-child(6) { animation-delay: 0.6s; }
  .timeline-item:nth-child(7) { animation-delay: 0.7s; }

  /* Position items on alternating sides */
  .timeline-item:nth-child(odd) {
    left: 0;
  }

  .timeline-item:nth-child(even) {
    left: 50%;
  }

  /* The dot on the timeline */
  .timeline-item::after {
    content: '';
    position: absolute;
    width: 16px;
    height: 16px;
    top: 1.5rem;
    background-color: var(--timeline-dot-color);
    border: 3px solid var(--timeline-bg);
    border-radius: 50%;
    z-index: 1;
  }

  .timeline-item:nth-child(odd)::after {
    right: -8px; /* half of width */
  }

  .timeline-item:nth-child(even)::after {
    left: -8px; /* half of width */
  }
  
  /* The content card */
  .timeline-content {
    padding: 1.5rem;
    background: var(--timeline-card-bg);
    border-radius: 8px;
    box-shadow: 0 4px 12px var(--timeline-card-shadow);
    position: relative;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  /* Interactive hover effect */
  .timeline-content:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px var(--timeline-card-shadow);
  }

  .timeline-date {
    display: block;
    font-size: 0.85rem;
    font-weight: 700;
    color: var(--timeline-date-color);
    margin-bottom: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
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
    background-image: linear-gradient(var(--timeline-link-color), var(--timeline-link-color));
    background-position: 0% 100%;
    background-repeat: no-repeat;
    background-size: 0% 2px;
    transition: background-size .3s;
  }

  .timeline-content a:hover {
    background-size: 100% 2px;
  }

  /* Keyframe animation for items appearing */
  @keyframes slideInUp {
    from {
      opacity: 0;
      transform: translateY(30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* Responsive adjustments for mobile */
  @media screen and (max-width: 768px) {
    .timeline::before {
      left: 15px; /* Move line to the left */
    }

    .timeline-item {
      width: 100%;
      padding-left: 45px; /* Space for line and dot */
      padding-right: 15px;
      left: 0 !important; /* Override the 'left: 50%' for even items */
    }

    .timeline-item::after {
      left: 7px; /* Position dot on the line */
    }
  }
</style>

## Latest News

<ul class="timeline">
  
  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-25" class="timeline-date">August 25, 2025</time>
      <p> Will be doing a 8 hour invited guest workshop in ML, DL & RL @ GLA university organised by IEEE Student Council on August 30 and 31st.</p>
    </div>
  </li>
  
  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-15" class="timeline-date">August 15, 2025</time>
      <p>Started working on two projects led by Amitava Das: neural genomics (<a href="https://pragyaai.github.io/ndna/" target="_blank" rel="noopener">project page</a>) and spatial reasoning in 3D.</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-15" class="timeline-date">August 15, 2025</time>
      <p>Participated in <a href="https://www.icts.res.in/program/DSPOM" target="_blank" rel="noopener">Data Science: Probabilistic and Optimization Methods II</a> at the International Centre for Theoretical Sciences (ICTS).</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-07-22" class="timeline-date">July 22, 2025</time>
      <p>Graduated from CMI with an M.Sc. in Data Science.</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-07-07" class="timeline-date">July 07, 2025</time>
      <p>Participated in <a href="https://mmlabiitg.github.io/lava2025/" target="_blank" rel="noopener">LAVA 2025</a> — an 8-day Summer School on AI & ML for Computer Vision and Language Modelling.</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-06-08" class="timeline-date">June 08, 2025</time>
      <p>Will be joining IISc–TCS Innovation Labs!</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-04-05" class="timeline-date">April 05, 2025</time>
      <p>Appeared for the last exam of my Master’s degree at CMI.</p>
    </div>
  </li>
</ul>
