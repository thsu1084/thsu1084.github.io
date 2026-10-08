---
layout: page
title: SetPieceRAG
description: Domain-specific retrieval-augmented generation for soccer video question answering.
importance: 1
category: research
---

**Youngseon Kim**, Jongmin Lee  
**CVPR 2026 · CVSports Workshop · Spotlight**

[Read the paper](https://openaccess.thecvf.com/content/CVPR2026W/CVsports/html/Kim_SetPieceRAG_Domain-Specific_RAG_for_Knowledge-Intensive_Soccer_VQA_with_Large_Language_CVPRW_2026_paper.html) · [View the poster](https://bluedream1121.github.io/spatial-intelligence-lab/images/publications/cvprw26-poster.png) · [Back to portfolio](/)

## Problem

Knowledge-intensive questions about soccer broadcasts require facts about players, teams, and historical context that are not directly visible in the video.

## Approach

SetPieceRAG connects visual information with domain-specific external knowledge. It uses CLIP, SoccerWiki, and web search to retrieve evidence for multimodal question answering, alongside task-specific adaptations including LoRA and image preprocessing.

## Evaluation

The work evaluates task-specific approaches on SoccerNet VQA. The full experimental setup and results are available in the published paper linked above.

![SetPieceRAG research poster](https://bluedream1121.github.io/spatial-intelligence-lab/images/publications/cvprw26-poster.png)
