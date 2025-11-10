---
layout: page
title: Projects
permalink: /Projects/
---
# Projects
# selected projects

<div class="projects-grid">

  <article class="project">
    <img src="/images/unwritten.png" alt="thumbnail">
    <div>
      <h3>Language Models Surface the Unwritten Code of Science and Society</h3>
      <p><strong>Honglin Bao</strong>, Siyang Wu*, <strong>Jiwoong Choi*</strong>, <strong>Yingrong Mao*</strong>, James A. Evans  
      <em>(Under Review), Dec 2025</em></p>
      <p class="buttons">
        <a class="btn" href="/files/unwritten-code-abstract.html">ABS</a>
        <a class="btn" href="/files/unwritten-code-paper.html">HTML</a>
      </p>
    </div>
  </article>

  <article class="project">
    <img src="/images/unwritten.png" alt="thumbnail">
    <div>
      <h3>Academic Simulacra: Forecasting Research Ideas through Multi-Agent LLM Simulations</h3>
      <p><u>Jiwoong Choi</u>, Donghyun Kang, <strong>Yingrong Mao</strong>, James Evans  
      <em>(Poster) ACM Collective Intelligence, Aug 2025</em></p>
      <p class="buttons">
        <a class="btn" href="/files/simulacra-abs.html">ABS</a>
        <a class="btn" href="/files/simulacra.html">HTML</a>
      </p>
    </div>
  </article>

  <!-- copy/paste more <article> blocks as needed -->

</div>

<style>
.page__content {
  max-width: 1000px;      /* limits total width */
  margin: 0 auto;         /* centers it horizontally */
  padding: 0 40px;        /* adds left/right spacing */
}

.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 28px;
}

.project {
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 24px;
  align-items: start;
  padding: 14px;
  border-radius: 14px;
  box-shadow: 0 2px 18px rgba(0,0,0,.06);
  background: #fff;
}

.project img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 10px;
  border: 1px solid #eee;
}

.project h3 { margin: 0 0 6px; }
.project p { margin: 6px 0; }

.buttons .btn {
  display: inline-block;
  padding: 6px 10px;
  border: 1px solid #222;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.85rem;
  margin-right: 8px;
}

@media (max-width: 900px){
  .project { grid-template-columns: 1fr; }
  .project img { height: 200px; }
}
</style>
