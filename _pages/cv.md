---
layout: page
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div class="cv-header">
  <a class="cv-btn" href="/files/cv.pdf" download>Download CV (PDF)</a>
  <a class="cv-btn outline" href="/files/cv.pdf" target="_blank" rel="noopener">Open in new tab</a>
</div>

<div class="cv-viewer">
  <!-- Prefer native PDF embedding; falls back gracefully -->
  <object data="/files/cv.pdf" type="application/pdf" class="cv-embed">
    <embed src="/files/cv.pdf" type="application/pdf" class="cv-embed"/>
    <p>
      Your browser can’t display the PDF inline.
      <a href="/files/cv.pdf" target="_blank" rel="noopener">Click here to open the CV</a>
      or use the download button above.
    </p>
  </object>
</div>

<style>
/* Header actions */
.cv-header {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin: 8px 0 16px 0;
}
.cv-btn {
  display: inline-block;
  padding: 8px 14px;
  border-radius: 10px;
  text-decoration: none;
  border: 1px solid currentColor;
  font-size: 0.95rem;
  line-height: 1.2;
}
.cv-btn.outline { background: transparent; }

/* Viewer box */
.cv-viewer {
  background: #fff;
  border: 1px solid #eee;
  border-radius: 14px;
  box-shadow: 0 2px 18px rgba(0,0,0,.06);
  overflow: hidden;
}

/* Responsive PDF frame */
.cv-embed {
  width: 100%;
  height: min(82vh, 1200px);  /* nicely fills the screen without overflows */
  display: block;
}

/* Optional: give the page comfortable side padding like your Projects page */
.page__content, .page__inner, .page {
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 40px;
}
@media (max-width: 900px){
  .page__content, .page__inner, .page { padding: 0 20px; }
}
</style>
