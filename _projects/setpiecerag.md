---
layout: page
title: SetPieceRAG
description: Domain-Specific RAG for Knowledge-Intensive Soccer VQA with Large Language Models
img: assets/img/setpiecerag/teaser.png
importance: 1
category: research
related_publications: true
---

<div class="text-center">

<h2>SetPieceRAG</h2>

<p>
<strong>Domain-Specific RAG for Knowledge-Intensive Soccer VQA with Large Language Models</strong>
</p>

<p>
<strong>Youngseon Kim</strong> and Jongmin Lee
</p>

<p>
CVSports Workshop @ CVPR 2026
</p>

<p>
<a href="/assets/pdf/setpiecerag.pdf" class="btn btn-sm btn-outline-primary" role="button">Paper</a>
<a href="/assets/pdf/setpiecerag_poster.pdf" class="btn btn-sm btn-outline-primary" role="button">Poster</a>
</p>

</div>

---

## Overview

SetPieceRAG is a domain-specific retrieval-augmented generation framework for
knowledge-intensive soccer video question answering.

While multimodal large language models can recognize many visual elements in
broadcast soccer videos, they often struggle with questions requiring
domain-specific, historical, or long-tail football knowledge.

SetPieceRAG addresses this limitation by retrieving relevant soccer knowledge
and grounding the model's reasoning in external domain-specific evidence.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/setpiecerag/teaser.png"
       title="SetPieceRAG overview"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
SetPieceRAG augments multimodal reasoning with domain-specific soccer knowledge
for knowledge-intensive video question answering.
</div>

---

## Motivation

Soccer broadcasts contain information that cannot always be inferred directly
from visual observations.

Questions may require knowledge about players, teams, competitions, historical
events, rules, or other contextual information that is not explicitly visible
in the video.

Large multimodal models may therefore generate plausible but incorrect answers
when the necessary soccer knowledge is missing.

Our key idea is simple:

> Retrieve the relevant soccer knowledge before asking the model to answer
> knowledge-intensive questions.

---

## Framework

SetPieceRAG combines video understanding with a domain-specific retrieval
pipeline.

The system retrieves soccer-related evidence relevant to the question and
provides this information together with the visual observation to the
multimodal language model.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/framework.png"
       title="SetPieceRAG framework"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
Overview of the SetPieceRAG framework.
</div>

---

## Key Results

SetPieceRAG substantially improves performance on knowledge-intensive soccer
VQA categories.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/results.png"
       title="SetPieceRAG results"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
Comparison between the baseline multimodal model and SetPieceRAG.
</div>

Some representative improvements include:

- **Q1:** 66% → **96%**
- **Q4:** 5% → **97%**

These results demonstrate the importance of external domain knowledge for
questions that cannot be reliably solved from visual evidence alone.

---

## Qualitative Examples

The following examples illustrate how retrieved soccer knowledge helps the
model answer questions that would otherwise require information beyond the
video itself.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/qualitative.png"
       title="SetPieceRAG qualitative examples"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

---

## CVSports @ CVPR 2026

SetPieceRAG was presented at the **CVSports Workshop at CVPR 2026**.

It was a great opportunity to present our work, discuss soccer video
understanding and multimodal reasoning with other researchers, and receive
valuable feedback from the computer vision and sports analytics communities.

### Presentation

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/presentation_01.jpg"
       title="Presenting SetPieceRAG at CVSports"
       class="img-fluid rounded z-depth-1" %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/presentation_02.jpg"
       title="CVSports presentation"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
Presenting SetPieceRAG at the CVSports Workshop @ CVPR 2026.
</div>

### Conference Moments

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/workshop_01.jpg"
       title="CVSports Workshop"
       class="img-fluid rounded z-depth-1" %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/group_01.jpg"
       title="CVPR 2026"
       class="img-fluid rounded z-depth-1" %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
       path="assets/img/setpiecerag/group_02.jpg"
       title="CVPR 2026"
       class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
Moments from CVSports and CVPR 2026.
</div>

---

## Paper

{% cite Kim_2026_CVPR %}

---

## Citation

```bibtex
@InProceedings{Kim_2026_CVPR,
  author    = {Kim, Youngseon and Lee, Jongmin},
  title     = {SetPieceRAG: Domain-Specific RAG for Knowledge-Intensive Soccer VQA with Large Language Models},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  month     = {June},
  year      = {2026},
  pages     = {10009--10018}
}
