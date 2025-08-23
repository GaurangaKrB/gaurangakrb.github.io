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
    max-width: 600px;               /* narrower for readability */
    margin: 3rem auto;              /* vertical space + centered */
    padding-left: 1rem;             /* space for the border */
    font-size: 1.8rem;              /* large but not overwhelming */
    line-height: 1.4;               /* comfortable linespacing */
    font-style: italic;             /* keeps the “quote” feel */
    color: currentColor;            /* adapts to light/dark mode */
    border-left: 4px solid #007acc; /* accent color on the left */
  }

  .hero-quote footer {
    margin-top: 1rem;
    font-size: 1rem;                /* smaller author line */
    font-style: normal;             /* remove italic for credit */
    font-weight: 500;
    color: currentColor;
    opacity: 0.75;                  /* a bit muted */
    text-align: left;               /* align to the main text */
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


I am a researcher in AI and ML. My primary research areas include Causal AI, RL, and Gen AI. Additionally, I apply ML methodologies to interdisciplinary problems across Computational Biology, Public Health, Computational Linguistics (e.g., Psychology).

I transitioned from the graduate program in Mathematics at IIT Kharagpur to complete my Master’s degree in Data Science at the Chennai Mathematical Institute (CMI), graduating in 2025. In 2024, I was honored to receive the [Khorana Scholarship](https://iusstf.org/khorana-program-for-scholars) to spend my summer at Harvard Medical School under the mentorship of [Prof. Yu-Hua Tseng](https://yhtsenglab.org/).

Outside my professional pursuits, I cherish diverse intellectual and recreational activities: cinematic arts (especially dramatic narratives), Chess, puzzle-solving, competitive programming, travel, photography, sketching, and writing philosophical and biographical articles. You can explore more of my thoughts and experiences in the [blogs](https://gaurangakrb.github.io/year-archive/) section.

I am always eager to connect, exchange ideas, and collaborate. Please feel free to reach out through any of my social media platforms.

<style>
  /* news-feed container */
  .news-list {
    list-style: none;
    padding: 0;
    margin: 2rem 0;
  }

  /* each news item */
  .news-item {
    display: flex;
    align-items: flex-start;
    border-bottom: 1px solid #e0e0e0;
    padding: 1rem 0;
  }
  .news-item:last-child {
    border-bottom: none;
  }

  /* date on the left: inherits theme text color, then mutes via opacity */
  .news-item time {
    flex: 0 0 120px;
    color: currentColor;
    opacity: 0.6;
    font-weight: bold;
  }

  /* content on the right */
  .news-content {
    flex: 1;
  }
  .news-content a {
    font-size: 1.05rem;
    font-weight: 600;
    color: #007acc;
    text-decoration: none;
  }
  .news-content a:hover {
    text-decoration: underline;
  }
  .news-content p {
    margin: 0.25rem 0 0;
    color: #333;
    font-size: 0.95rem;
  }
</style>

## Latest News

<ul class="news-list">
  
  <li class="news-item">
    <time datetime="2025-08-15">Aug 15, 2025</time>
    <div class="news-content">
      Started working in two projects @ led by Amitava Das. One in the revolutionary idea of neural genomics (<a href="https://pragyaai.github.io/ndna/"
      target="_blank" rel="noopener"></a>) and one in spatial reasoning in 3d.
    </div>
  </li>
  
  <li class="news-item">
    <time datetime="2025-08-15">Aug 15, 2025</time>
    <div class="news-content">
      Participate in this amazing, fully-funded event, Data Science: Probabilistic And Optimization Methods II (<a href="https://www.icts.res.in/program/DSPOM"          target="_blank" rel="noopener"></a>) held @ International Centre for Theoretical Sciences (ICTS).
    </div>
  </li>

  <li class="news-item">
    <time datetime="2025-07-07">Jul 07, 2025</time>
    <div class="news-content">
      Graduated from CMI with M.Sc. in Data Science today!
    </div>
  </li>

  <li class="news-item">
    <time datetime="2025-07-07">Jul 7, 2025</time>
    <div class="news-content">
      Participated in the LAVA 2025 - 8-day Summer School on AI and ML for Computer Vision and Language Modelling (<a href="https://mmlabiitg.github.io/lava2025/"       target="_blank" rel="noopener"></a>) 
    </div>
  </li>
  
  <li class="news-item">
    <time datetime="2025-06-08">Jun 08, 2025</time>
    <div class="news-content">
      Will be joining IISc-TCS Innovation labs!
    </div>
  </li>

  <li class="news-item">
    <time datetime="2025-04-05">April 05, 2025</time>
    <div class="news-content">
      Appereared for the last exam of my Masters Degree @ CMI.
    </div>
  </li>
</ul>
