---
layout: page
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div class="cv-page">
  <div class="cv-header">
    <a class="cv-btn" href="{{ '/files/cv.pdf' | relative_url }}" download>Download CV (PDF)</a>
    <a class="cv-btn outline" href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
  </div>

  <div class="cv-viewer">
    <object data="{{ '/files/cv.pdf' | relative_url }}" type="application/pdf" class="cv-embed">
      <embed src="{{ '/files/cv.pdf' | relative_url }}" type="application/pdf" class="cv-embed"/>
      <p>
        Your browser can’t display the PDF inline.
        <a href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Click here to open the CV</a>
        or use the download button above.
      </p>
    </object>
  </div>
</div>

<style>
/* === Page Wrapper (Centers the Content) === */
.cv-page {
  max-width: 1000px;      /* consistent with projects page */
  margin: 0 auto;         /* centers horizontally */
  padding: 0 40px;        /* left/right spacing */
}

/* Header Buttons */
.cv-header {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin: 8px 0 20px 0;
  justify-content: center;   /* centers the buttons themselves */
}
.cv-btn {
  display: inline-block;
  padding: 8px 14px;
  border-radius: 10px;
  text-decoration: none;
  border: 1px solid currentColor;
  font-size: 0.95rem;
  line-height: 1.2;
  transition: background 0.2s ease;
}
.cv-btn.outline {
  background: transparent;
}
.cv-btn:hover {
  background: rgba(0, 0, 0, 0.05);
}

/* PDF Viewer Box */
.cv-viewer {
  background: #fff;
  border: 1px solid #eee;
  border-radius: 14px;
  box-shadow: 0 2px 18px rgba(0,0,0,.06);
  overflow: hidden;
  padding: 10px;
}

/* PDF Embed Frame */
.cv-embed {
  width: 100%;
  height: min(82vh, 1200px);
  display: block;
}

/* Responsive layout */
@media (max-width: 900px) {
  .cv-page { padding: 0 20px; }
  .cv-embed { height: 80vh; }
}
</style>
