---
title: 'Bias: Endangering Species and Performance'
summary: 'An Evaluation of SpeciesNet on Leopard Classification as a Feasibility Study for Endangered Species'
tags:
  - Software
featured: true
draft: false
date: "2025-10-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Tali Weinstein
  focal_point: Smart

links:
  - icon: face-smile
    icon_pack: far
    name: Prize
    url: 'https://docs.google.com/document/d/e/2PACX-1vTw8WXh6QaCM5g9wmhdyDRfbvwQ_l85z_VPzLx7zsI5T7iasJ4MQZLZufd6ozd1BMdgv3aG7KUS2zii/pub'
  - icon: map
    icon_pack: fas
    name: Poster
    url: 'Poster.pdf'

---

The project “Bias: Endangering Species and Model Performance” investigates how long-tail imbalance and contextual bias in global wildlife classification models disadvantage endangered and data-deficient species. Using camera-trap data from Malawi’s Nkhotakota Reserve, the team evaluated SpeciesNet’s performance across species of differing IUCN conservation status. Results revealed a stark disparity in recall between common and vulnerable species (0.68 for impalas vs. 0.18 for leopards), exposing systematic underrepresentation of endangered taxa. To address this, the project fine-tuned SpeciesNet using taxonomic grouping, IUCN Red List metadata, and uncertainty quantification methods such as Generalized Additive Models (GAMs) and calibrated mixture models. These techniques improved endangered-species recall, introduced interpretable diagnostics for failure modes like nocturnality and foliage occlusion, and allowed the model to flag “unknown” cases for ranger review.

Beyond its technical contributions, the work aims to propose a new evaluation framework emphasizing endangered-species recall and calibration metrics aligned with conservation risk, filling a key gap in current literature. By bridging ecological insight with machine learning rigor, the project advances African-led AI for biodiversity monitoring and conservation safety. The work was recognized with 3rd place at the [2025 African Computer Vision Summer School Hackathon](https://www.linkedin.com/feed/update/urn:li:activity:7356360785473789953/) and a Poster Award at the [2025 Deep Learning Indaba](https://docs.google.com/document/d/e/2PACX-1vTw8WXh6QaCM5g9wmhdyDRfbvwQ_l85z_VPzLx7zsI5T7iasJ4MQZLZufd6ozd1BMdgv3aG7KUS2zii/pub), underscoring its scientific and societal impact

### Skills: 
AI for Conservation, Bias Evaluation, Model Validation, Cross-Disciplinary Collaboration

