---
permalink: /
title: "Zhouyou Lai"
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /cv/
  - /cv
---

## About
{: #about }

I am **Zhouyou Lai**, a master's student in **Electronic Information at Shanghai Jiao Tong University**. I received my bachelor's degree in Software Engineering from Sichuan University.

My interests include **LLM inference optimization, KV cache management, and heterogeneous computing**, with a particular focus on efficient long-context inference.


## Education
{: #education }

### Shanghai Jiao Tong University

<div class="education__meta">
  <strong>Master's in Electronic Information</strong>
  <span>Sep 2025 - Mar 2028 (expected)</span>
  <span>Shanghai, China</span>
</div>

### Sichuan University

<div class="education__meta">
  <strong>Bachelor's in Software Engineering</strong>
  <span>Sep 2021 - Jul 2025</span>
  <span>Chengdu, China</span>
</div>

- **GPA: 3.88 / 4.00**; ranked **8 / 210 (top 4%)**.
- Selected coursework: Computer Organization and Architecture (97), Database Systems and Information Management (96), Calculus I-1 (96), Introduction to Software Engineering (95), Discrete Mathematics (94), Data Structures and Algorithms (94), Probability and Statistics (92), and Computer Networks (91).

## Publications
{: #publications }

<div class="publication" markdown="1">
<div class="publication__media" markdown="0">
<a class="publication__thumbnail" href="{{ '/images/publish/PACG-Figure-2.png' | relative_url }}">
  <img src="{{ '/images/publish/PACG-Figure-2.png' | relative_url }}" alt="PACG framework: rollout and claim routing, counterfactual persistence, and credit gating" width="964" height="543" loading="lazy">
</a>
</div>

<div class="publication__details" markdown="1">

### Visual sensitivity is not claim retractability: persistence-aware credit assignment for multimodal reinforcement learning

Zhongan Bi, Kepeng Lin, Xuanang Gao, Yuhan Sun, and Lianrun Zhang

**Submitted to ICLR 2027** &middot; Preprint, 2026

[arXiv:2609.36572](https://arxiv.org/abs/2609.36572) &middot; [PDF]({{ '/files/12312_Visual_Sensitivity_Is_No.pdf' | relative_url }})

Persistence-Aware Credit Gating (PACG) addresses the gap between visual sensitivity and claim retractability in multimodal reinforcement learning. A counterfactual diagnostic identifies visual claims that persist despite changes to the image; PACG then reduces positive training credit for unusually persistent claims without requiring supported/unsupported labels or adding inference cost. Experiments show improved benchmark accuracy and more retractable unsupported claims.

</div>
</div>

<div class="publication" markdown="1">
<div class="publication__media" markdown="0">
<a class="publication__thumbnail" href="{{ '/images/publish/CMIB-Figure1-1.png' | relative_url }}">
  <img src="{{ '/images/publish/CMIB-Figure1-1.png' | relative_url }}" alt="CMIB framework for histology and genomic feature extraction, multimodal aggregation, and information bottleneck" width="1430" height="434" loading="lazy">
</a>
</div>

<div class="publication__details" markdown="1">

### CMIB: A Cross Modal Interaction with Information Bottleneck Framework for Multimodal Survival Analysis

**Zhou Lai**, Lifan Long, et al. &middot; **First author**

**Venue:** 2024 IEEE International Conference on Cybernetics and Intelligent Systems (CIS) and IEEE International Conference on Robotics, Automation and Mechatronics (RAM)

**Published:** August 8, 2024

[DOI: 10.1109/CIS-RAM61939.2024.10673062](https://doi.org/10.1109/CIS-RAM61939.2024.10673062) &middot; [IEEE Xplore](https://ieeexplore.ieee.org/document/10673062) &middot; Corpus ID: 272724858

CMIB integrates histology images and genomic data for multimodal survival analysis. Private and common feature extraction blocks (PFEB and CFEB) separate modality-specific and shared information, while co-attention models their interactions. A multimodal information bottleneck (MIB) filters redundancy and noise from the fused representation. Experiments on three public TCGA datasets showed improved performance over the state-of-the-art methods evaluated in the paper.

</div>
</div>

## Projects
{: #projects }

### Huawei: Optimizing Heterogeneous LLM Serving on a Serverless AI Platform

**Sep 2025 - Nov 2025**

This project addressed GPU memory bottlenecks in long-context inference with dynamic sparse attention through a **hot/cold tiered KV cache architecture**, coordinating GPU and host memory to support long-sequence inference.

- **Inference benchmarking:** Evaluated models including Qwen2.5-14B-1M and DeepSeek-R1-Distill-Llama-70B.
- **Performance validation:** Tested fine-grained offloading, sparse-attention-based cache hotness management, and coalesced transfers on DeepSeek-70B, with throughput increasing from **15.91 to 31.94 tokens/s**.
- **Technical reporting:** Contributed the experimental validation and technical challenges sections of the final project report; studied related work including GQA, Longformer, vLLM, and FlashAttention.
- **Outcomes:** The project produced a patent application for a hot/cold tiered KV cache method for dynamic sparse attention (case reference: 92091772) and received Huawei's 2025 Spark Award in its technical challenge program.

## Honors & Awards
{: #honors }

<dl class="honors__list">
  <dt>Oct 2024</dt>
  <dd>National Scholarship</dd>
  <dt>Aug 2024</dt>
  <dd>National Second Prize, China Software Cup University Software Design Competition (top 2%)</dd>
  <dt>Oct 2023 &amp; Oct 2022</dt>
  <dd>First-Class Comprehensive Scholarship (two consecutive years)</dd>
</dl>
