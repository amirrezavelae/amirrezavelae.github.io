---
title: "Towards Fair Retrieval:  Controlling Bias through a Backpack-Inspired Architecture"
collection: publications 
category: manuscripts 
permalink: /publication/bp_ranker
excerpt: "A fairer ranking method built on Backpack language models"
date: 2025-09-02 
venue: "Preprint"
paperurl: "http://amirrezavelae.github.io/files/backpack__preprint.pdf"  
---
Women are still underrepresented pretty much everywhere power hangs out—about 27% of MPs worldwide (Aug 2025) and ~27.5% of managerial roles (2022). Not exactly a rounding error. See <a href="https://data.ipu.org/women-averages/?date_year=2025&date_month=08" target="_blank">IPU Parline</a> and <a href="https://www.unwomen.org/sites/default/files/2024-09/progress-on-the-sustainable-development-goals-the-gender-snapshot-2024-en.pdf" target="_blank">UN Women</a>.

**tl;dr:** Ever searched “developer” images and gotten wall-to-wall dudes—or “nurse” and seen mostly women? That’s data bias doing cosplay as relevance. This paper uses Backpack language models <a href="https://arxiv.org/abs/2305.16765" target="_blank">(J. Hewitt et al., 2023)</a> (which split each token into multiple, interpretable “sense” vectors) to identify which senses carry gender signal and then *turns those down* at inference—no retraining, just fewer stereotype vibes. On MS MARCO and a gender-bias IR benchmark, it cuts RaB/ARaB (less skew) <a href="https://arxiv.org/abs/2005.00372" target="_blank">(N. Rekabsaz et al., 2020)</a> with only a tiny dent in NDCG/MRR, and the Backpack ranker still edges a similarly sized GPT-2 baseline.

Download the preprint from <a href="http://amirrezavelae.github.io/files/backpack__preprint.pdf" target="_blank">here</a>.

