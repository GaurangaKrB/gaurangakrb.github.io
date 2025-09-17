---
permalink: /
title: "Welcome to My Website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<blockquote class="hero-quote">
  “The greater danger for most of us lies not in setting our aim too high and falling short; but in setting our aim too low, and achieving our mark.”
  <footer>&mdash; Michelangelo Buonarroti</footer>
</blockquote>

<style>
  .hero-quote {
    max-width: 650px;
    margin: 3rem auto 4rem;
    padding-left: 1.5rem;
    font-size: 1.6rem;
    line-height: 1.5;
    font-style: italic;
    color: #555;
    border-left: 3px solid #007acc;
  }

  .hero-quote footer {
    margin-top: 1rem;
    font-size: 1rem;
    font-style: normal;
    font-weight: 400;
    color: #777;
    text-align: left;
  }

  [data-theme="dark"] .hero-quote {
    color: #bbb;
    border-left-color: #3498db;
  }

  [data-theme="dark"] .hero-quote footer {
    color: #999;
  }

  @media (max-width: 600px) {
    .hero-quote {
      font-size: 1.3rem;
      margin: 2rem auto 3rem;
    }
    .hero-quote footer {
      font-size: 0.9rem;
    }
  }
</style>

I am an AI/ML researcher with a focus on **Causal AI**, **Reinforcement Learning**, and **Generative AI**. My work also involves applying machine learning to interdisciplinary challenges in Computational Biology, Public Health, and Computational Linguistics.

My academic path led me from a graduate program in Mathematics at IIT Kharagpur to a Master of Science in Data Science from the Chennai Mathematical Institute (CMI), which I completed in 2025. During my studies, I was selected as a 2024 **[Khorana Scholar](https://iusstf.org/khorana-program-for-scholars)**, an opportunity that allowed me to conduct summer research at Harvard Medical School under the mentorship of **[Prof. Yu-Hua Tseng](https://yhtsenglab.org/)**.

Beyond research, I am passionate about cinema, chess, competitive programming, and travel. I also enjoy writing, and you can find a collection of my thoughts and articles in the [blogs](https://gaurangakrb.github.io/year-archive/) section.

Always open to connecting with fellow researchers and enthusiasts to exchange ideas or explore potential collaborations. Please feel free to reach out.

<style>
  :root {
    --accent-color: #007acc;
    --text-color-primary: #333;
    --text-color-secondary: #6c757d;
    --card-bg: #ffffff;
    --card-shadow: rgba(0, 0, 0, 0.06);
    --card-shadow-hover: rgba(0, 0, 0, 0.12);
    --border-color: #e9ecef;
    --timeline-line-color: #dee2e6;
  }

  [data-theme="dark"] {
    --accent-color: #3498db;
    --text-color-primary: #e0e0e0;
    --text-color-secondary: #a0a0a0;
    --card-bg: #2c2c2c;
    --card-shadow: rgba(0, 0, 0, 0.2);
    --card-shadow-hover: rgba(0, 0, 0, 0.3);
    --border-color: #444;
    --timeline-line-color: #555;
  }

  .timeline {
    position: relative;
    max-width: 900px;
    margin: 4rem auto;
    padding: 0;
    list-style: none;
  }

  .timeline::before {
    content: '';
    position: absolute;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 2px;
    height: 100%;
    background-color: var(--timeline-line-color);
  }
  
  .timeline-item {
    padding: 1rem 2.5rem;
    position: relative;
    width: 50%;
    opacity: 0;
    animation: slideInUp 0.6s ease-out forwards;
  }
  
  /* Stagger animation */
  .timeline-item:nth-child(1) { animation-delay: 0.1s; }
  .timeline-item:nth-child(2) { animation-delay: 0.2s; }
  .timeline-item:nth-child(3) { animation-delay: 0.3s; }
  .timeline-item:nth-child(4) { animation-delay: 0.4s; }
  .timeline-item:nth-child(5) { animation-delay: 0.5s; }
  .timeline-item:nth-child(6) { animation-delay: 0.6s; }
  .timeline-item:nth-child(7) { animation-delay: 0.7s; }
  .timeline-item:nth-child(8) { animation-delay: 0.8s; }

  .timeline-item:nth-child(odd) { left: 0; }
  .timeline-item:nth-child(even) { left: 50%; }

  .timeline-item::after {
    content: '';
    position: absolute;
    width: 14px;
    height: 14px;
    top: 1.8rem;
    background-color: var(--card-bg);
    border: 3px solid var(--accent-color);
    border-radius: 50%;
    z-index: 1;
    transition: transform 0.3s ease;
  }

  .timeline-item:nth-child(odd)::after { right: -7px; }
  .timeline-item:nth-child(even)::after { left: -7px; }
  
  .timeline-item:hover::after {
    transform: scale(1.1);
  }
  
  .timeline-content {
    padding: 1.5rem;
    background: var(--card-bg);
    border-radius: 8px;
    border: 1px solid var(--border-color);
    box-shadow: 0 4px 12px var(--card-shadow);
    position: relative;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .timeline-content:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px var(--card-shadow-hover);
  }

  .timeline-date {
    display: block;
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--text-color-secondary);
    margin-bottom: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  .timeline-content p {
    margin: 0;
    font-size: 0.95rem;
    line-height: 1.6;
    color: var(--text-color-primary);
  }
  
  .timeline-content a {
    font-weight: 600;
    color: var(--accent-color);
    text-decoration: none;
    background-image: linear-gradient(var(--accent-color), var(--accent-color));
    background-position: 0% 100%;
    background-repeat: no-repeat;
    background-size: 0% 2px;
    transition: background-size .3s;
  }

  .timeline-content a:hover {
    background-size: 100% 2px;
  }

  @keyframes slideInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @media screen and (max-width: 768px) {
    .timeline::before { left: 12px; }
    .timeline-item { width: 100%; padding-left: 35px; padding-right: 15px; left: 0 !important; }
    .timeline-item::after { left: 5px; }
  }
</style>

## Latest News

<ul class="timeline">

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-09-11" class="timeline-date">September 11, 2025</time>
      <p>Participated in the symposium on Artificial Intelligence and Pharmaceutical Medicine-2025 co hosted by Pfizer and IBSE, IITM.</p>
    </div>
  </li>
  
  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-30" class="timeline-date">August 30-31, 2025</time>
      <p>Invited to lead an 8-hour guest workshop on ML, Deep Learning & RL at GLA University, organized by the IEEE Student Council.</p>
    </div>
  </li>
  
  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-15" class="timeline-date">August 15, 2025</time>
      <p>Began work on two new research projects under Prof. Amitava Das: Neural Genomics (<a href="https://pragyaai.github.io/ndna/" target="_blank" rel="noopener">project page</a>) and Spatial Reasoning in 3D.</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-08-01" class="timeline-date">August 2025</time>
      <p>Attended <a href="https://www.icts.res.in/program/DSPOM" target="_blank" rel="noopener">Data Science: Probabilistic and Optimization Methods II</a> at ICTS, a program sponsored by Google DeepMind, Microsoft Research and Ashoka University.</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-07-22" class="timeline-date">July 22, 2025</time>
      <p>Graduated with 1st Class Distinction in M.Sc. Data Science from Chennai Mathematical Institute (CMI).</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-07-07" class="timeline-date">July 07, 2025</time>
      <p>Participated in <a href="https://mmlabiitg.github.io/lava2025/" target="_blank" rel="noopener">LAVA 2025</a>, an 8-day Summer School on AI for Computer Vision and Language Modelling @ IIT Guwahati..</p>
    </div>
  </li>

  <li class="timeline-item">
    <div class="timeline-content">
      <time datetime="2025-06-08" class="timeline-date">June 08, 2025</time>
      <p>Excited to announce I will be joining the IISc–TCS Innovation Labs!</p>
    </div>
  </li>

</ul>
