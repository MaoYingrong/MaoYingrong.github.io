---
layout: page
title: Projects
permalink: /projects/
---

# Projects
<span class="section-kicker">selected projects</span>

<div class="projects-grid">

  <article class="project">
    <img src="/images/unwritten.png" alt="Diagram for Unwritten Code project" loading="lazy">
    <div>
      <h3>Language Models Surface the Unwritten Code of Science and Society</h3>
      <p><strong>Honglin Bao</strong>, Siyang Wu*, <strong>Jiwoong Choi*</strong>, <strong>Yingrong Mao*</strong>, James A. Evans<br>
      <em>(Under Review), Dec 2025</em></p>
      <p class="buttons">
        <a class="btn" href="/files/unwritten-code-abstract.html">ABS</a>
        <a class="btn" href="/files/unwritten-code-paper.html">HTML</a>
      </p>
    </div>
  </article>

  <article class="project">
    <img src="/images/animation.png" alt="Embeddings and clusters visualization" loading="lazy">
    <div>
      <h3>Academic Simulacra: Forecasting Research Ideas through Multi-Agent LLM Simulations</h3>
      <p><u>Jiwoong Choi</u>, Donghyun Kang, <strong>Yingrong Mao</strong>, James Evans<br>
      <em>(Poster) ACM Collective Intelligence, Aug 2025</em></p>
      <p class="buttons">
        <a class="btn" href="/files/simulacra-abs.html">ABS</a>
        <a class="btn" href="/files/simulacra.html">HTML</a>
      </p>
    </div>
  </article>

  <!-- duplicate <article> blocks for more projects -->

</div>

<style>
/* Center & contain the page body */
.page__content, .page__inner, .page {
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 40px;
}

/* small label under the page title */
.section-kicker {
  display: inline-block;
  margin: -6px 0 18px 0;
  letter-spacing: .06em;
  text-transform: lowercase;
  color: #777;
}

/* card list */
.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 28px;
}

/* card */
.project {
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 24px;
  align-items: start;
  padding: 14px;
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 2px 18px rgba(0,0,0,.06);
}

/* thumbnail */
.project img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 10px;
  border: 1px solid #eee;
}

/* text spacing */
.project h3 { margin: 0 0 6px; }
.project p  { margin: 6px 0; }

/* buttons */
.buttons .btn {
  display: inline-block;
  padding: 6px 12px;
  border: 1px solid currentColor;
  border-radius: 8px;
  text-decoration: none;
  font-size: 0.85rem;
  margin-right: 8px;
  line-height: 1.2;
  background: transparent;
}
.buttons .btn:hover { filter: brightness(0.9); }

/* mobile */
@media (max-width: 900px){
  .project { grid-template-columns: 1fr; }
  .project img { height: 200px; }
  .page__content, .page__inner, .page { padding: 0 20px; }
}
</style>
