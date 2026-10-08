---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
---

<style>
.cv-wrap{max-width:920px;margin:0 auto;padding:10px 0 40px;color:#191f28}
.cv-hero{display:grid;grid-template-columns:1fr 160px;gap:36px;align-items:center;padding:18px 0 28px;border-bottom:1px solid #e5eaf0}
.cv-name{font-size:42px;line-height:1.1;letter-spacing:-1.8px;margin:0 0 10px;font-weight:800}
.cv-role{font-size:17px;color:#586575;margin:0 0 14px}
.cv-summary{font-size:15px;line-height:1.75;color:#586575;max-width:680px;margin:0}
.cv-photo{width:150px;height:190px;object-fit:cover;object-position:center 25%;border-radius:16px;border:1px solid #e5eaf0;box-shadow:0 8px 24px #23304a10}
.cv-links{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}
.cv-link{display:inline-block;padding:8px 12px;border-radius:8px;background:#f5f7fb;font-size:13px;font-weight:700}
.cv-section{padding:30px 0 4px}
.cv-section h2{font-size:23px;letter-spacing:-.5px;margin:0 0 16px}
.cv-grid{display:grid;grid-template-columns:150px 1fr;gap:20px;padding:15px 0;border-top:1px solid #eef1f4}
.cv-grid:first-of-type{border-top:0}
.cv-date{font-size:13px;color:#2463eb;font-weight:750}
.cv-item h3{font-size:16px;margin:0 0 4px}
.cv-item p{margin:3px 0;color:#586575;font-size:14px;line-height:1.65}
.cv-item ul{margin:8px 0 0;padding-left:18px;color:#586575;font-size:14px;line-height:1.65}
.cv-tags{display:flex;flex-wrap:wrap;gap:7px;margin-top:10px}
.cv-tags span{font-size:12px;background:#f5f7fb;border-radius:6px;padding:5px 8px;color:#526070}
.cv-pub{padding:17px 0;border-top:1px solid #eef1f4}
.cv-pub:first-of-type{border-top:0}
.cv-pub-title{font-weight:750;font-size:15px;line-height:1.55}
.cv-pub-meta{font-size:13px;color:#586575;margin-top:4px}
.cv-note{font-size:12px;color:#7b8794;margin-top:6px}
@media(max-width:700px){
  .cv-hero{grid-template-columns:1fr}
  .cv-photo{width:130px;height:165px}
  .cv-name{font-size:34px}
  .cv-grid{grid-template-columns:1fr;gap:6px}
}
</style>

<div class="cv-wrap">

<div class="cv-hero">
  <div>
    <h1 class="cv-name">Youngseon Kim</h1>
    <p class="cv-role">M.S. Student in Computer Engineering · Chung-Ang University</p>
    <p class="cv-summary">
      AI researcher working on multimodal learning, computer vision, vision-language models,
      video understanding, and retrieval-augmented generation. My research focuses on grounding
      visual reasoning with external knowledge and building practical multimodal systems for
      real-world video understanding.
    </p>
    <div class="cv-links">
      <a class="cv-link" href="/">Portfolio</a>
      <a class="cv-link" href="https://github.com/thsu1084">GitHub ↗</a>
      <a class="cv-link" href="https://bluedream1121.github.io/spatial-intelligence-lab/">Spatial Intelligence Lab ↗</a>
    </div>
  </div>
  <img class="cv-photo" src="/assets/img/prof_pic.jpg" alt="Youngseon Kim" />
</div>

<section class="cv-section">
  <h2>Research Interests</h2>
  <div class="cv-tags">
    <span>Multimodal AI</span>
    <span>Computer Vision</span>
    <span>Vision-Language Models</span>
    <span>Video Understanding</span>
    <span>Retrieval-Augmented Generation</span>
    <span>Knowledge Grounding</span>
  </div>
</section>

<section class="cv-section">
  <h2>Education</h2>
  <div class="cv-grid">
    <div class="cv-date">M.S. · 2027 expected</div>
    <div class="cv-item">
      <h3>Chung-Ang University</h3>
      <p>Computer Engineering</p>
      <p>Advisor: Prof. Jongmin Lee</p>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Selected Publications</h2>

  <div class="cv-pub">
    <div class="cv-pub-title">
      SetPieceRAG: Domain-Specific RAG for Knowledge-Intensive Soccer VQA with Large Language Models
    </div>
    <div class="cv-pub-meta">
      <strong>Youngseon Kim</strong>, Jongmin Lee · CVPR 2026 Workshop on Computer Vision in Sports (CVSports) · Spotlight
    </div>
    <div class="cv-note">
      <a href="https://openaccess.thecvf.com/content/CVPR2026W/CVsports/html/Kim_SetPieceRAG_Domain-Specific_RAG_for_Knowledge-Intensive_Soccer_VQA_with_Large_Language_CVPRW_2026_paper.html">Paper ↗</a>
    </div>
  </div>

  <div class="cv-pub">
    <div class="cv-pub-title">SoccerNet 2026 Challenges Results</div>
    <div class="cv-pub-meta">
      Anthony Cioppa et al., including <strong>Youngseon Kim</strong> and Jongmin Lee · ACCV 2026 · Co-author
    </div>
    <div class="cv-note">
      <a href="https://arxiv.org/abs/2607.07320">Preprint ↗</a>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Selected Research</h2>

  <div class="cv-grid">
    <div class="cv-date">2026</div>
    <div class="cv-item">
      <h3>SetPieceRAG / SoccerPlaybook</h3>
      <p>
        Task-adaptive knowledge grounding for soccer video question answering with multimodal large language models.
      </p>
      <ul>
        <li>Domain-specific RAG with visual retrieval and external soccer knowledge.</li>
        <li>Task-dependent routing, fallback strategies, LoRA adaptation, and video preprocessing.</li>
        <li>Evaluated on knowledge-intensive and perception-oriented soccer VQA settings.</li>
      </ul>
    </div>
  </div>

  <div class="cv-grid">
    <div class="cv-date">2026</div>
    <div class="cv-item">
      <h3>SoccerCanon</h3>
      <p>
        Benchmark and training-free aggregation framework for canonical player identity recognition
        from challenging soccer broadcast imagery.
      </p>
      <ul>
        <li>Combines face, appearance, kit, and jersey-number evidence.</li>
        <li>Studies uncertainty-aware aggregation and rank fusion under incomplete visual evidence.</li>
      </ul>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Honors & Support</h2>
  <div class="cv-grid">
    <div class="cv-date">2026</div>
    <div class="cv-item">
      <h3>CVSports @ CVPR 2026</h3>
      <p>Spotlight presentation for SetPieceRAG.</p>
    </div>
  </div>
  <div class="cv-grid">
    <div class="cv-date">Graduate</div>
    <div class="cv-item">
      <h3>Research Support</h3>
      <p>NRF Master's Research Fellowship · WISET research support.</p>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Technical Skills</h2>
  <div class="cv-grid">
    <div class="cv-date">ML / Vision</div>
    <div class="cv-item">
      <p>PyTorch · CLIP / OpenCLIP · Vision-Language Models · LoRA · RAG · FAISS · Multimodal Evaluation</p>
    </div>
  </div>
  <div class="cv-grid">
    <div class="cv-date">Research</div>
    <div class="cv-item">
      <p>Benchmark design · Ablation studies · Retrieval systems · Video QA · Experimental analysis · Academic writing</p>
    </div>
  </div>
</section>

</div>
