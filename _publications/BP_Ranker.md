---
title: "Towards Fair Retrieval:  Controlling Bias through a Backpack-Inspired Architecture"
collection: publications 
category: manuscripts 
date: 2025-09-02 
venue: "Journal Name" 
paperurl: "files/backpack__preprint.pdf"  
permalink: /publication/2025-09-02-my-paper 
excerpt: "Short summary of the paper." 
citation: "Lastname, F. (2025). Paper Title. Journal Name."
---
tl;dr — The paper proposes a fairer ranking method built on Backpack language models: it splits each token into multiple “sense” vectors, estimates which senses are gender-sensitive, then reweights them at inference to suppress bias—no retraining required. In tests (MS MARCO + a gender-bias IR benchmark), this cut gender skew (lower RaB/ARaB) with only a small hit to ranking quality, and the Backpack ranker still beat a similarly sized GPT-2 baseline. Limitations: the model is relatively small, results focus on binary gender, and bias suppression doesn’t always change the final order of top items. 
 Also builds on the Backpack LM architecture for interpretable “sense” control. 
arxiv.org