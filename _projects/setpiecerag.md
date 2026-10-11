---
layout: page
title: SetPieceRAG
description: Domain-specific retrieval-augmented generation for soccer video question answering.
importance: 1
category: research
---

**Youngseon Kim**, Jongmin Lee  
**CVPR 2026 · CVSports Workshop · Spotlight**

[Read the paper](https://openaccess.thecvf.com/content/CVPR2026W/CVsports/html/Kim_SetPieceRAG_Domain-Specific_RAG_for_Knowledge-Intensive_Soccer_VQA_with_Large_Language_CVPRW_2026_paper.html) · [View the poster](#poster) · [Back to portfolio](/)

## Problem

Knowledge-intensive questions about soccer broadcasts require facts about players, teams, and historical context that are not directly visible in the video.

## Approach

SetPieceRAG connects visual information with domain-specific external knowledge. It uses CLIP, SoccerWiki, and web search to retrieve evidence for multimodal question answering, alongside task-specific adaptations including LoRA and image preprocessing.

## Evaluation

The work evaluates task-specific approaches on SoccerNet VQA. The full experimental setup and results are available in the published paper linked above.

<div id="poster"></div>

<a id="setpiecerag-poster-link" href="#poster">
  <img id="setpiecerag-poster" alt="SetPieceRAG research poster" style="width: 100%; height: auto;" />
</a>

<small>Image credit: Ujishadow / Wikimedia Commons, CC BY-SA 4.0.</small>

<script>
  (function () {
    const parts = Array.from({ length: 7 }, (_, i) =>
      fetch(`/assets/img/setpiecerag-poster-parts/${i}.txt`).then((response) => {
        if (!response.ok) throw new Error(`Failed to load poster part ${i}`);
        return response.text();
      })
    );

    Promise.all(parts)
      .then((chunks) => {
        const src = "data:image/webp;base64," + chunks.join("");
        const image = document.getElementById("setpiecerag-poster");
        const link = document.getElementById("setpiecerag-poster-link");
        image.src = src;
        link.href = src;
      })
      .catch((error) => console.error("Unable to load SetPieceRAG poster:", error));
  })();
</script>
