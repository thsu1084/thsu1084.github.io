---
layout: page
permalink: /cv/
title: CV
nav: false
---

<style>
.cv-page{
  max-width:900px;
  margin:0 auto;
  padding:28px 10px 60px;
  color:#191f28;
  font-family:Inter,-apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans KR",sans-serif;
}
.cv-topbar{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:18px;
  margin-bottom:34px;
}
.cv-home{
  font-size:13px;
  font-weight:700;
  color:#2463eb;
}
.cv-print{
  font-size:13px;
  font-weight:700;
  color:#586575;
}
.cv-header{
  padding-bottom:24px;
  border-bottom:2px solid #191f28;
}
.cv-name{
  font-size:42px;
  line-height:1.05;
  margin:0 0 8px;
  letter-spacing:-1.8px;
  font-weight:800;
}
.cv-subtitle{
  font-size:16px;
  font-weight:650;
  margin:0 0 3px;
}
.cv-location{
  font-size:14px;
  color:#586575;
  margin:0;
}
.cv-contact{
  margin-top:14px;
  display:flex;
  flex-wrap:wrap;
  gap:10px 18px;
  font-size:13px;
  color:#586575;
}
.cv-contact a{color:#2463eb}
.cv-section{
  display:grid;
  grid-template-columns:185px 1fr;
  gap:28px;
  padding:26px 0;
  border-bottom:1px solid #e5eaf0;
}
.cv-label{
  font-size:13px;
  font-weight:800;
  letter-spacing:.03em;
  text-transform:uppercase;
}
.cv-body{
  font-size:14px;
  line-height:1.72;
  color:#3d4855;
}
.cv-body p{margin:0 0 9px}
.cv-entry{
  margin-bottom:20px;
}
.cv-entry:last-child{margin-bottom:0}
.cv-entry-head{
  display:flex;
  justify-content:space-between;
  gap:20px;
  align-items:baseline;
  margin-bottom:4px;
}
.cv-entry-title{
  font-weight:750;
  color:#191f28;
}
.cv-date{
  white-space:nowrap;
  color:#586575;
  font-size:13px;
}
.cv-role{
  font-size:13px;
  color:#586575;
  margin-bottom:6px;
}
.cv-pub{
  margin-bottom:14px;
}
.cv-pub:last-child{margin-bottom:0}
.cv-pub-title{
  color:#191f28;
  font-weight:700;
}
.cv-small{
  font-size:13px;
  color:#586575;
}
.cv-skills{
  display:grid;
  grid-template-columns:135px 1fr;
  gap:7px 16px;
}
.cv-skill-label{
  font-weight:700;
  color:#191f28;
}
@media(max-width:720px){
  .cv-section{grid-template-columns:1fr;gap:10px}
  .cv-entry-head{display:block}
  .cv-date{display:block;margin-top:2px}
  .cv-name{font-size:34px}
  .cv-skills{grid-template-columns:1fr}
}
@media print{
  .cv-topbar{display:none}
  .cv-page{max-width:none;padding:0}
  .cv-section{break-inside:avoid}
}
</style>

<div class="cv-page">

  <div class="cv-topbar">
    <a class="cv-home" href="/">← Portfolio</a>
    <a class="cv-print" href="javascript:window.print()">Print / Save as PDF</a>
  </div>

  <header class="cv-header">
    <h1 class="cv-name">Youngseon Kim</h1>
    <p class="cv-subtitle">M.S. Student, Department of Computer Science and Engineering</p>
    <p class="cv-location">Chung-Ang University, Seoul, Republic of Korea</p>
    <div class="cv-contact">
      <span>E-mail: thsu1084@cau.ac.kr</span>
      <a href="https://github.com/thsu1084">GitHub ↗</a>
      <a href="/">Portfolio ↗</a>
    </div>
  </header>

  <section class="cv-section">
    <div class="cv-label">Research Areas</div>
    <div class="cv-body">
      <p><strong>Multimodal AI, Retrieval-Augmented Generation, Vision-Language Understanding, Medical AI</strong></p>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Research Interests</div>
    <div class="cv-body">
      <p>
        Reliable and knowledge-grounded AI for multimodal reasoning and high-stakes decision support,
        with interests in domain-specific retrieval-augmented generation, vision-language understanding,
        open-vocabulary object detection, and safe medical recommendation.
      </p>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Education</div>
    <div class="cv-body">
      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-entry-title">Chung-Ang University</div>
          <div class="cv-date">2025 – Present</div>
        </div>
        <div class="cv-role">M.S. Student, Department of Computer Science and Engineering</div>
        <p>
          Advisor: Prof. Jongmin Lee. Research area: multimodal AI, retrieval-augmented generation,
          vision-language understanding, open-vocabulary object detection, and safe medication recommendation.
        </p>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Publications & Manuscripts</div>
    <div class="cv-body">
      <div class="cv-pub">
        <div class="cv-pub-title">
          Youngseon Kim and Jongmin Lee, “SetPieceRAG: Domain-Specific RAG for Knowledge-Intensive Soccer VQA with Large Language Models.”
        </div>
        <div class="cv-small">CVSPORTS Workshop, CVPR, 2026 · Accepted</div>
      </div>
      <div class="cv-pub">
        <div class="cv-pub-title">
          Youngseon Kim, “Training-Free Textual Prescription Refinement for Safe Medication Recommendation.”
        </div>
        <div class="cv-small">Submitted to NeurIPS 2026 · Under Review</div>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Funded Research & Fellowship</div>
    <div class="cv-body">
      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-entry-title">National Research Foundation of Korea Master’s Student Research Fellowship</div>
          <div class="cv-date">2025 – Present</div>
        </div>
        <div class="cv-role">Master’s Student Researcher</div>
        <p>
          Selected for the NRF Master’s Student Research Fellowship in the science and engineering field.
          Research topic: “A Study on Object Detection using Open-Vocabulary Classification based on Natural Language Descriptions,”
          focusing on natural-language-driven open-vocabulary object detection and RoI-level visual-text matching.
        </p>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-entry-title">WISET Women Graduate Student Engineering Research Team Program</div>
          <div class="cv-date">Apr. 2025 – Oct. 2025</div>
        </div>
        <div class="cv-role">Research Lead, Chung-Ang University</div>
        <p>
          Led a funded research team project titled “Intelligent Text-Linked Suspect Tracking System Using Multimodal AI.”
          Managed research planning, experiment design, team coordination, result analysis, and report preparation.
        </p>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Challenge Experience</div>
    <div class="cv-body">
      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-entry-title">SoccerNet Challenge 2026 – Visual Question Answering</div>
          <div class="cv-date">2026</div>
        </div>
        <div class="cv-role">Participant</div>
        <p>
          Ranked 15th out of 143 participants on the official challenge leaderboard.
          Developed a task-specific soccer VQA system combining domain-specific retrieval-augmented generation,
          CLIP-based entity grounding, external knowledge integration, LLM ensembling, LoRA-based adaptation,
          super-resolution preprocessing, and object-centric video analysis.
        </p>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Technical Skills</div>
    <div class="cv-body">
      <div class="cv-skills">
        <div class="cv-skill-label">Programming</div>
        <div>Python, Java, SQL, Bash, LaTeX</div>

        <div class="cv-skill-label">Deep Learning</div>
        <div>PyTorch, Hugging Face Transformers, PEFT, LoRA, Unsloth</div>

        <div class="cv-skill-label">Vision-Language / RAG</div>
        <div>CLIP, InternVL, Qwen-VL, Gemini, FAISS, vector databases, prompt engineering</div>

        <div class="cv-skill-label">Computer Vision</div>
        <div>Open-vocabulary object detection, visual retrieval, object tracking, Re-ID, super-resolution, SAHI</div>

        <div class="cv-skill-label">Medical AI</div>
        <div>MIMIC-III, medication recommendation, DDI-aware evaluation, clinical note processing</div>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-label">Language Skills</div>
    <div class="cv-body">
      <p><strong>Korean:</strong> Native &nbsp;&nbsp; <strong>English:</strong> Professional research reading and writing</p>
    </div>
  </section>

</div>
