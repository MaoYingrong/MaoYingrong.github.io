---
layout: page
title: Projects
permalink: /Projects/
---

<div class="projects-page">
  <hr>
  <hr>
  <h1>Working Papers</h1>

  <div class="projects-grid">

    <article class="project">
      <img src="/images/animation.png" alt="Embeddings and clusters visualization" loading="lazy">
      <div>
        <h3>Academic Simulacra: Forecasting Research Ideas through Multi-Agent LLM Simulations</h3>
        <p>Jiwoong Choi*, Yingrong Mao*, Donghyun Kang, James Evans<br> 
        <em>(*equal contribution)</em></p>
        <details class="abs" data-abstract>
          <summary class="btn">Abstract</summary>
          <div class="abs-body">
            <p>
Large language models (LLMs) trained on massive corpora of human knowledge show strong abilities in reasoning, question answering, and knowledge synthesis. Linked to large-scale scholarly records, they can approximate scientific trajectories and plausible alternatives. We present a framework that simulates scholarly conversations among multi-agent LLMs instantiated as digital twins of real researchers, each grounded in publication histories. Modeling 8,269 authors of 2024 papers across nine flagship computer-science conferences, agents propose and refine hypothetical 2024 research ideas beyond the models’ knowledge cutoff. Generated ideas are compared with actual papers using semantic-similarity and convex-hull analyses at the author and conference levels. At the author level, cross-classification shows strong correspondence between generated and focal classifications (94.4% inside–inside; 85.3% outside–outside), indicating that simulations approximate researchers’ research directions. At the conference level, simulations produced at least one idea outside both 2023 and 2024 convex hulls for 99.1% of focal papers, but these ideas were more recombinatorial and less feasible than human-authored ones. Overall, the results suggest that LLM-based simulations mirror established patterns of scientific production but tend to extend into less immediately feasible directions, recombining existing ideas.
            </p>
          </div>
        </details>
      </div>
    </article>

        <article class="project">
      <img src="/images/unwritten.png" alt="Diagram for Unwritten Code project" loading="lazy">
      <div>
        <h3>Language Models Surface the Unwritten Code of Science and Society</h3>
        <p>Honglin Bao, Siyang Wu*, Jiwoong Choi*, Yingrong Mao*, James A. Evans<br>
        <em>(*equal contribution)</em></p>
        <details class="abs" data-abstract>
          <summary class="btn">Abstract</summary>
          <div class="abs-body">
            <p>
              This paper calls on the research community not only to investigate how human biases are inherited by large language models (LLMs) but also to explore how these biases in LLMs can be leveraged to make society's "unwritten code" - such as implicit stereotypes and heuristics - visible and accessible for critique. We introduce a conceptual framework through a case study in science: uncovering hidden rules in peer review - the factors that reviewers care about but rarely state explicitly due to normative scientific expectations. The idea of the framework is to push LLMs to speak out their heuristics through generating self-consistent hypotheses - why one paper appeared stronger in reviewer scoring - among paired papers submitted to 45 academic conferences, while iteratively searching deeper hypotheses from remaining pairs where existing hypotheses cannot explain. We observed that LLMs' normative priors about the internal characteristics of good science extracted from their self-talk, e.g., theoretical rigor, were systematically updated toward posteriors that emphasize storytelling about external connections, such as how the work is positioned and connected within and across literatures. Human reviewers tend to explicitly reward aspects that moderately align with LLMs' normative priors (correlation = 0.49) but avoid articulating contextualization and storytelling posteriors in their review comments (correlation = -0.14), despite giving implicit reward to them with positive scores. These patterns are robust across different models and out-of-sample judgments. We discuss the broad applicability of our proposed framework, leveraging LLMs as diagnostic tools to amplify and surface the tacit codes underlying human society, enabling public discussion of revealed values and more precisely targeted responsible AI.
            </p>
          </div>
        </details>
        
        <p class="buttons">
          <a class="btn" href="https://arxiv.org/abs/2505.18942">Link</a>
        </p>
      </div>
    </article>

    <!-- add more <article> blocks as needed -->

  </div>
  
  <hr>
  <hr>
  <h1>Works in Progress</h1>
  <!-- <span class="section-kicker">Works in Progress</span> -->

  <div class="projects-grid">

    <article class="project">
      <img src="/images/memes.png" alt="Diagram for Unwritten Code project" loading="lazy">
      <div>
        <h3>Meme Adaptability and Popularity: Investigating the Evolutionary Dynamics of Internet Meme Templates</h3>
        <p>Yingrong Mao<br></p>
        <p class="buttons">
          <a class="btn" href="/files/IC2S2_extended_abstract.pdf">Link</a>
        </p>
      </div>
    </article>


    <!-- add more <article> blocks as needed -->

  </div>
</div>

<style>
/* OUR OWN WRAPPER — wins regardless of theme layout */
.projects-page{
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 40px;
}

/* if the theme still squeezes it, force it */
.initial-content .projects-page{
  max-width: 1000px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 40px !important;
  padding-right: 40px !important;
}

/* small label below the title */
.section-kicker{
  display:inline-block; margin:-6px 0 18px 0; letter-spacing:.06em; color:#777;
}

/* card list */
.projects-grid{ display:grid; grid-template-columns:1fr; gap:28px; }

/* card */
.project{
  display:grid; grid-template-columns:240px 1fr; gap:24px; align-items:start;
  padding:14px; border-radius:14px; background:#fff; box-shadow:0 2px 18px rgba(0,0,0,.06);
}

/* thumbnail */
.project img{ width:100%; height:160px; object-fit:cover; border-radius:10px; border:1px solid #eee; }

/* text */
.project h3{ margin:0 0 6px; } 
.project p{ margin:6px 0; }

/* buttons */
.buttons .btn{
  display:inline-block; padding:6px 12px; border:1px solid currentColor; border-radius:8px;
  text-decoration:none; font-size:.85rem; margin-right:8px; line-height:1.2;
}

@media (max-width: 900px){
  .project{ grid-template-columns:1fr; }
  .project img{ height:200px; }
  .projects-page{ padding:0 20px; }
}
</style>
