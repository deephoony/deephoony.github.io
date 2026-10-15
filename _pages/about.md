---
layout: about
permalink: /
subtitle: kevinjeong-at-snu-ac-kr

profile:
  align: right
  image: chang-hoon-jeong.jpg
  image_circular: true
  more_info:

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  .post article {
    --global-theme-color: #0b3d91;
    --global-hover-color: #062c6e;
  }

  html[data-theme="dark"] .post article {
    --global-theme-color: #58a6ff;
    --global-hover-color: #79b8ff;
  }

  .pub-marker {
    display: inline-block;
    width: 0.68em;
    height: 0.68em;
    margin-right: 0.38em;
    border-radius: 50%;
    vertical-align: 0.06em;
  }

  .pub-conference {
    background: #c97979;
  }

  .pub-journal {
    background: #c5a654;
  }

  .pub-workshop {
    background: #6f9b7e;
  }

  .pub-book {
    background: #6d90b8;
  }

  .pub-review {
    background: #9a7cad;
  }

  .pub-note {
    font-size: 0.85em;
    opacity: 0.75;
    margin-top: -0.4rem;
  }

  .page-toc {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 1.2rem;
    margin: 1.8rem 0 0.5rem;
    padding-top: 0.9rem;
    border-top: 1px solid var(--global-divider-color);
    font-size: 0.95em;
  }

  .page-toc a {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .page-toc a:hover {
    color: var(--global-hover-color);
    text-decoration: underline;
  }

  .post article h2 {
    scroll-margin-top: 5rem;
  }

  @media (prefers-reduced-motion: no-preference) {
    html {
      scroll-behavior: smooth;
    }
  }
</style>

I am a Ph.D. candidate in the Department of [Computer Science and Engineering](https://cse.snu.ac.kr/en) at [Seoul National University](https://en.snu.ac.kr/index.html), advised by [Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html).

My research focuses on how reinforcement-learning agents can learn to learn: building useful task representations, generalizing across tasks, and adapting quickly to unfamiliar environments. I am especially interested in meta-reinforcement learning and offline reinforcement learning, where I study task representations that stay reliable as the task changes. I also have a strong interest in continual reinforcement learning and out-of-distribution generalization.

Before beginning my Ph.D., I worked as a researcher at the AI Institute of Seoul National University and received my B.S. in Computer Science and Engineering from [Dongguk University](https://www.dongguk.edu/eng/main).

Outside research, I play tennis 🎾 and Go ⚫⚪, and I am a big fan of [Carlos Alcaraz](https://www.instagram.com/carlitosalcarazz/) in tennis and [Shin Jin-seo](https://en.wikipedia.org/wiki/Shin_Jin-seo) in Go. If you enjoy either game and would like to play, please feel free to reach out. I would be happy to meet you on the court or over the board! 😊

<nav class="page-toc" aria-label="On this page">
  <a href="#research-interests">Research Interests</a>
  <a href="#selected-publications">Selected Publications</a>
  <a href="#teaching-experience">Teaching Experience</a>
</nav>

## Research Interests

- Meta-reinforcement learning
- Offline reinforcement learning
- Generalization in reinforcement learning
- Continual reinforcement learning
- Out-of-distribution generalization

## Selected Publications

<p>
  <strong>
    <span class="pub-marker pub-conference" role="img" aria-label="Conference"></span>1 Conference ·
    <span class="pub-marker pub-journal" role="img" aria-label="Journal"></span>1 Journal ·
    <span class="pub-marker pub-workshop" role="img" aria-label="Workshop"></span>1 Workshop ·
    <span class="pub-marker pub-book" role="img" aria-label="Book"></span>1 Book ·
    <span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>9 Under Review
  </strong>
</p>

<div class="publications">
  <ol class="bibliography">
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Trust, but Verify: Test-Time Task Inference in Offline Meta-Reinforcement Learning</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin<sup>*</sup>, Hanwool Sul<sup>*</sup>, Luna Sung-eun Jang<sup>*</sup>, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>What In-Context Reinforcement Learners Infer About Unseen Tasks</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin<sup>*</sup>, Hanwool Sul<sup>*</sup>, Luna Sung-eun Jang<sup>*</sup>, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Exploratory Prompting for In-Context Reinforcement Learning</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Luna Sung-eun Jang, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Fixed-Rank Subspace Protection with Neuron Recycling for Task-Free Continual Learning</div>
      <div class="author">Kisung Shin, <strong>Chang-Hoon Jeong</strong>, Hanwool Sul, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Decision Diversity Should Match Linguistic Ambiguity: Distributional Alignment for Offline Meta-Reinforcement Learning</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin, Hanwool Sul, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Reframing Video Inverse Tone Mapping as Blind Posterior Inference via Latent Luminance Supervision</div>
      <div class="author">Hanwool Sul, <strong>Chang-Hoon Jeong</strong>, Kisung Shin, Bomseok Park, Donghoon Cha, Hansl von Kwon, Ku DoHyung, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Blind Spots of Quality Metrics for Unobserved Regions in SDR-to-HDR Video</div>
      <div class="author">Hanwool Sul, <strong>Chang-Hoon Jeong</strong>, Kisung Shin, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Where Does Forgetting Live in Actor-Critic? Component-Wise Diagnosis and Targeted Protection in Continual Reinforcement Learning</div>
      <div class="author">Kisung Shin, <strong>Chang-Hoon Jeong</strong>, Hanwool Sul, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-review" role="img" aria-label="Under Review"></span>Latent-Conservative Optimization for Robust Offline Meta-Reinforcement Learning</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin, <a href="https://yeonjisong.github.io/">Yeon-Ji Song</a>, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Under Review</em></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-journal" role="img" aria-label="Journal"></span>Drift-Gated Ensemble Pessimism for Offline Meta-Reinforcement Learning Robust to Behavior-Policy Shift</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Journal of KIISE (JOK)</em>, 2026</div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-conference" role="img" aria-label="Conference"></span>Pessimistic Latent Task-aware Optimization for Robust Offline Meta-Reinforcement Learning</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, Kisung Shin, Hanwool Sul, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><em>Conference on Neural Information Processing Systems (NeurIPS)</em>, 2026</div>
      <div class="links"><a class="btn btn-sm z-depth-0" href="https://arxiv.org/abs/2610.15428" role="button">PDF</a><a class="btn btn-sm z-depth-0" href="https://github.com/deephoony/plato" role="button">Code</a></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-workshop" role="img" aria-label="Workshop"></span>Sign and Magnitude: Two Aspects of Parameter Drift in Continual Learning</div>
      <div class="author">Kisung Shin, <strong>Chang-Hoon Jeong</strong>, Hanwool Sul, and <a href="https://bi.snu.ac.kr/members/byoung-tak-zhang.html">Byoung-Tak Zhang</a><sup>&dagger;</sup></div>
      <div class="periodical"><a href="https://openreview.net/group?id=NeurIPS.cc/2026/Workshop/CL4FMAgents/Authors&amp;referrer=%5BHomepage%5D(%2F)"><em>NeurIPS 2026 Workshop CL4FMAgents</em></a></div>
      <div class="links"><a class="btn btn-sm z-depth-0" href="https://openreview.net/pdf?id=UBL0WZFVWy" role="button">PDF</a></div>
    </li>
    <li>
      <div class="title"><span class="pub-marker pub-book" role="img" aria-label="Book"></span>Meta-Learning for Everyone: Building Few-Shot Learning Models and Fast Reinforcement Learning Agents with PyTorch</div>
      <div class="author"><strong>Chang-Hoon Jeong</strong>, <a href="https://www.linkedin.com/in/seung-hyun-lee-abb99a109/">Seung-Hyun Lee</a>, Dongmin Lee, Luna Sung-eun Jang, <a href="https://www.seungjaeryanlee.com/">Seungjae Ryan Lee</a>, and Seungje Yoon; reviewed by <a href="https://sites.google.com/view/sungjoon-choi/home?authuser=0">Sungjoon Choi</a></div>
      <div class="periodical"><em>Wikibooks</em>, 2022</div>
      <div class="links"><a class="btn btn-sm z-depth-0" href="https://wikibook.co.kr/metalearning/" role="button">Book</a></div>
    </li>
  </ol>
</div>

<p class="pub-note"><sup>*</sup>Equal contribution as co-second authors. <sup>&dagger;</sup>Corresponding author.</p>

## Teaching Experience

- **Instructor** · Introduction to Artificial Intelligence, Duksung Women's University (Fall 2024)
- **Instructor** · Reinforcement Learning, Samsung Electronics Research (July 2018 – January 2019)
- **Teaching Assistant** · Artificial Intelligence, Seoul National University (Spring 2022, Spring 2023)
- **Teaching Assistant** · Data Structure, Dongguk University (Spring 2019)
- **Teaching Assistant** · Machine Learning, Dongguk University (Spring 2018)
