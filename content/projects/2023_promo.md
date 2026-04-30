---
title: "Precision Pricing at Scale: AI-Driven Margin Optimization for National Retail"
description: "Engineering a store-level price optimization engine for a major Canadian grocer, shifting from a \"one-size-fits-all\" promotion model to a localized, AI-assisted strategy across 1,000+ locations."
date: 2025-03-25T15:30:00-04:00
publishDate: 2025-03-25T15:30:00-04:00

image: "https://morganbye.com/assets/img/projects/supermarket.webp"
label: "Algorithmic Commerce"
tags: ["ai", "pricing"]
---

## The Business Context

In the low-margin world of grocery retail, promotions drive 40% of revenue. However, the retailer was trapped in a cycle of "repetitive promotion," applying identical pricing across vastly different demographics. This lack of granularity resulted in significant margin "leakage" and supply chain volatility.

## The Strategic Mandate

- **Localized Elasticity:** Moving from national pricing to store-cluster optimization based on local demand.
- **Waste Reduction:** Aligning promotional pricing with supply chain capacity to reduce the "bullwhip effect."
- **Merchant Empowerment:** Transitioning from manual spreadsheets to an "AI-augmented" planning workflow.

---

## The Strategic Approach

I led the design of a modular, hybrid solution that merged high-volume data engineering with advanced mathematical optimization.

Key Leadership Decisions:

- **Scalable Data Ingestion:** Architected a pipeline to process and normalize 24 billion transactional records, ensuring high-fidelity inputs for the forecasting models.
- **Hybrid Modeling (ML + Optimization):** Combined Machine Learning for demand forecasting with Mixed-Integer Non-Linear Programming (MINLP) to solve for the optimal balance of price, volume, and margin.
- **Human-in-the-Loop Design:** Prioritized the "Merchant UX," ensuring the AI acted as a co-pilot that experts could review and override, rather than a "black box" that alienated the domain specialists.

---

## What We Delivered

- **Dynamic Store Clustering:** Developed algorithms to group **1,000+ stores** by price sensitivity rather than just geography, uncovering hidden margin opportunities.
- **Automated Promotion Scheduling:** Engineered a scalable engine capable of generating full quarterly schedules while respecting complex business constraints (e.g., inventory limits, vendor contracts).
- **Production-Grade Vertex AI Pipeline:** Built an end-to-end MLOps workflow on Google Cloud to handle iterative A/B testing and model retraining at scale.

---

## The Strategic Impact

- **Direct Cash Flow:** Delivered an estimated **$85,000 CAD per store, per year** in free cash flow impact.
- **Margin Expansion:** Realized a **4.6% gross margin improvement** specifically on unadvertised promotional lines.
- **Operational Efficiency:** Freed merchant teams from manual data entry, allowing them to focus on high-level category strategy.
- **Supply Chain Stability:** Improved upstream visibility, reducing waste and overstocking by smoothing out promotional demand spikes.

---

## Infrastructure & Science Stack

- **Cloud Platform:** Google Cloud (BigQuery, Vertex AI, DataProc)
- **Orchestration:** Cloud Composer (Apache Airflow)
- **Optimization:** Mixed-Integer Programming & Hierarchical Clustering

Data Scale: **24B+ records** across 1,000+ stores

---

## Executive Reflection

This project was a masterclass in **Organizational Change Management** disguised as a tech project. In retail, data doesn't matter if the merchants don't trust the model. By building a transparent, high-performance system that delivered measurable cash flow, we proved that AI isn't a replacement for human judgment - it's the most powerful lever a merchant has to drive profitability in a hyper-competitive market.