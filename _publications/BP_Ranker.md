---
title: "Controlling Gender Bias in Retrieval"
collection: publications 
category: manuscripts 
permalink: /publication/bp_ranker
excerpt: "Converting Backpack language models into encoders to mitigate gender bias in ranking, without retraining."
date: 2025-11-01
venue: "ECIR 2026"
paperurl: "https://arxiv.org/abs/2511.00875"
citation: "Amirabbas Afzali*, Amirreza Velae*, Iman Ahmadi, and Mohammad Aliannejadi. &quot;Controlling Gender Bias in Retrieval.&quot; In Proceedings of ECIR 2026. (*Equal contribution)"
---
Women remain underrepresented pretty much everywhere power hangs out — about 27% of MPs worldwide (Aug 2025) and ~27.5% of managerial roles (2022). Not exactly a rounding error. See <a href="https://data.ipu.org/women-averages/?date_year=2025&date_month=08" target="_blank">IPU Parline</a> and <a href="https://www.unwomen.org/sites/default/files/2024-09/progress-on-the-sustainable-development-goals-the-gender-snapshot-2024-en.pdf" target="_blank">UN Women</a>.

**tl;dr:** Ever searched "developer" and gotten wall-to-wall men, or "nurse" and seen mostly women? That's data bias doing cosplay as relevance. This paper, with <a href="https://scholar.google.com/citations?user=yiZk6coAAAAJ&hl=en" target="_blank">Prof. Mohammad Aliannejadi</a>'s group at the University of Amsterdam, converts Backpack language models <a href="https://arxiv.org/abs/2305.16765" target="_blank">(J. Hewitt et al., 2023)</a> — which split each token into multiple, interpretable "sense" vectors — into an encoder, so the senses that carry gender signal can be identified and *turned down* at inference, with no retraining required. On MS MARCO and a gender-bias IR benchmark, it reduces RaB/ARaB skew <a href="https://arxiv.org/abs/2005.00372" target="_blank">(N. Rekabsaz et al., 2020)</a> with only a small cost to NDCG/MRR, and the resulting ranker still edges out a similarly sized GPT-2 baseline.

Read the paper on <a href="https://arxiv.org/abs/2511.00875" target="_blank">arXiv</a>.

