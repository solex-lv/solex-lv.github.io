---
permalink: /
title: ""
excerpt: "Song-Lin Lv is an M.S. student at Nanjing University, working on LLM/MLLM post-training, reinforcement learning, and vision-language models."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Song-Lin Lv** (吕松霖), an M.S. student in Computer Science and Technology at the School of Intelligence Science and Technology, **Nanjing University**. I am advised by Prof. [Lan-Zhe Guo](https://www.lamda.nju.edu.cn/guolz/) and work with [LAMDA](https://www.lamda.nju.edu.cn/). Before that, I received my B.Eng. in Artificial Intelligence from **Shandong University**.

<div class="research-interests" aria-label="Research interests">
  <div class="interest-label">Research Interests</div>
  <div class="interest-list">
    <span class="interest-tag interest-tag--llm">LLM/MLLM Post-training</span>
    <span class="interest-tag interest-tag--rl">Reinforcement Learning</span>
    <span class="interest-tag interest-tag--vlm">Vision-Language Models</span>
    <span class="interest-tag interest-tag--agent">Agentic AI</span>
  </div>
</div>

My research focuses on post-training large language models (LLMs) and multimodal large language models (MLLMs), including supervised fine-tuning, reinforcement learning, rubric-guided reward design, model distillation, and test-time performance improvement. I am also interested in reliable vision-language learning, especially parameter-efficient tuning, calibration, and semi-supervised self-training.

<span class="anchor" id="news"></span>

# News

<ul class="news-list">
  <li class="news-item">
    <span class="news-date">2026.07</span>
    <span class="news-body"><em><a href="https://arxiv.org/abs/2607.25659">CoRT</a></em> was released on arXiv, studying token-level credit assignment in rubric-guided GRPO.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026.05</span>
    <span class="news-body">Our work on open-world generalization of tool-use agents was accepted by <strong>ICML 2026</strong>.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026.05</span>
    <span class="news-body"><em>Bi-CoG</em> was accepted by <strong>IJCAI 2026</strong> as an <strong>Oral</strong> paper.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026.04</span>
    <span class="news-body">I joined Douyin AI Search at ByteDance as an LLM algorithm intern.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.08</span>
    <span class="news-body"><em>BMIP</em> was accepted by <strong>IJCAI 2025</strong> as an <strong>Oral</strong> paper.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.07</span>
    <span class="news-body">I joined Huawei Terminal BG, Xiaoyi Cloud Service Department, as an AI algorithm intern.</span>
  </li>
</ul>

<span class="anchor" id="publications"></span>

# Publications & Research

<sup>*</sup> denotes equal contribution. Selected works are listed below. To respect double-blind review, ongoing/submitted works that have not been publicly accepted are marked only with generic statuses and do not disclose target venues.

<section class="publication-section">
<h2>Published / Accepted</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2025</span>
      <span class="paper-note award">Oral</span>
    </div>
    <h3><a href="https://www.ijcai.org/proceedings/2025/655">BMIP: Bi-directional Modality Interaction Prompt Learning for VLM</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, Yu-Yang Chen, Zhi Zhou, Ming Yang, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--tuning">Prompt Learning</span></div>
    <p>We propose a parameter-efficient prompt-learning framework for CLIP-style vision-language models. BMIP learns prompts for the visual and textual modalities and enables bidirectional modality interaction to improve downstream representation learning.</p>
    <p class="pub-links"><a href="https://www.ijcai.org/proceedings/2025/655">Paper</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2026</span>
      <span class="paper-note award">Oral · 2026.05</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2510.20477">Bi-CoG: Bi-Consistency-Guided Self-Training for Vision-Language Models</a></h3>
    <p class="authors">Rui Zhu<sup>*</sup>, <strong>Song-Lin Lv</strong><sup>*</sup>, Zi-Kang Wang, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--ssl">Semi-Supervised Learning</span></div>
    <p>Bi-CoG leverages the original generalization ability of multiple VLMs for multi-view self-training on unlabeled data, improving semi-supervised learning under open-environment and VLM evaluation settings.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2510.20477">arXiv</a> / <a href="https://arxiv.org/pdf/2510.20477">PDF</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">ICML 2026</span>
      <span class="paper-note">2026.05</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2607.01084">Can Agents Generalize to the Open World? Unveiling the Fragility of Static Training in Tool Use</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong><sup>*</sup>, Weiming Wu<sup>*</sup>, Rui Zhu<sup>*</sup>, Zi-Jian Cheng<sup>*</sup>, Lan-Zhe Guo. Author order was determined by lottery.</p>
    <div class="paper-interests"><span class="interest-tag--agent">LLM Agents</span><span class="interest-tag--rl">LLM RL</span></div>
    <p>We study whether post-trained tool-use agents can generalize to open-world changes, including out-of-distribution tasks, tool-name updates, domain shifts, and unexpected tool errors. We compare SFT, RL, and SFT+RL pipelines and propose Perturbation-Augmented Fine-Tuning (PAFT) to improve robustness.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2607.01084">arXiv</a> / <a href="https://icml.cc/virtual/2026/poster/65179">PDF</a></p>
  </article>
</div>
</section>

<section class="publication-section">
<h2>Submitted / Preprints</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2607.25659">CoRT: Counterfactual Replay for Token-Level Rubric-Guided Policy Optimization</a></h3>
    <p class="authors">Bo-Wen Zhang, Junwei He, Wen Wang, <strong>Song-Lin Lv</strong>, Wentao Ma, Rongyi Lin, Shuhan Zhong, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--rl">LLM RL</span><span class="interest-tag--distill">Distillation</span></div>
    <p>CoRT studies token-level credit assignment in Rubric RL. It uses counterfactual replay to compare token-level likelihood differences with and without rubric conditioning, then redistributes GRPO advantages without adding a token-level scoring model or changing the original sequence-level reward.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2607.25659">arXiv</a> / <a href="https://arxiv.org/pdf/2607.25659">PDF</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3>Perception-Inference Decoupling: A Dual-Stage Framework to Boost LVLM Reasoning</h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, Yu-Yang Chen, Zhi Zhou, Ming Yang, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">MLLM</span><span class="interest-tag--reasoning">Reasoning</span></div>
    <p>We study visual perception hallucination and reasoning hallucination in MLLMs through an explicit two-stage optimization strategy that separates perception from inference.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3>ActionPRM: Learning Action-Level Process Reward Models for Pre-Execution Action Selection in Multimodal Agents</h3>
    <p class="authors">Yongqian Wen<sup>*</sup>, <strong>Song-Lin Lv</strong><sup>*</sup>, Ye Luo, Lan-Zhe Guo. Song-Lin Lv served as a mentor.</p>
    <div class="paper-interests"><span class="interest-tag--agent">Multimodal Agents</span><span class="interest-tag--rl">Process Reward Models</span></div>
    <p>ActionPRM learns action-level process reward models to evaluate candidate actions before tool execution, supporting action selection and tool-use optimization for multimodal agents.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2505.13317">Unlabeled Data or Pre-trained Model: Rethinking Semi-Supervised Learning and Pretrain-Finetuning</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, Rui Zhu, Tong Wei, Yu-Feng Li, Lan-Zhe Guo. Equal contribution.</p>
    <div class="paper-interests"><span class="interest-tag--ssl">Semi-Supervised Learning</span><span class="interest-tag--vlm">Pretrain-Finetuning</span></div>
    <p>We compare semi-supervised learning and pretrain-finetuning under data scarcity, summarizing the strengths and limitations of both paradigms and motivating future hybrid methods.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2505.13317">arXiv</a> / <a href="https://arxiv.org/pdf/2505.13317">PDF</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2501.19060">Shift-Aware Calibration for Fine-Tuned CLIP: Leveraging Image-Text Alignment</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, Yu-Yang Chen, Zhi Zhou, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--calibration">Calibration</span></div>
    <p>We leverage the calibration behavior of original CLIP to improve confidence estimation after fine-tuning, making VLMs more reliable and deployable under distribution shift.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2501.19060">arXiv</a> / <a href="https://arxiv.org/pdf/2501.19060">PDF</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Submitted</span>
    </div>
    <h3>DECOOP: Robust Prompt Tuning with Out-of-Distribution Detection</h3>
    <p class="authors">Zhi Zhou, <strong>Song-Lin Lv</strong>, Ming Yang, Jiang-Xin Shi, Lan-Zhe Guo, Yu-Feng Li.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Prompt Learning</span><span class="interest-tag--ood">OOD Detection</span></div>
    <p>DECOOP improves CLIP prompt tuning in open environments by combining multiple sub-experts with a general expert and falling back to the general expert under uncertainty.</p>
  </article>
</div>
</section>

<span class="anchor" id="experience"></span>

# Experience

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026.04 - Present</div>
    <div class="timeline-body"><strong>LLM Algorithm Intern</strong>, Douyin AI Search, ByteDance, Shanghai.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.07 - 2025.10</div>
    <div class="timeline-body"><strong>AI Algorithm Intern</strong>, Huawei Terminal BG, Xiaoyi Cloud Service Department, Shanghai.</div>
  </div>
</div>

<span class="anchor" id="education"></span>

# Education

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2024.09 - 2027.06</div>
    <div class="timeline-body"><strong>Nanjing University</strong>, M.S. in Computer Science and Technology, School of Intelligence Science and Technology. Advisor: Prof. <a href="https://www.lamda.nju.edu.cn/guolz/">Lan-Zhe Guo</a>; LAMDA. Awarded Outstanding Graduate Student of Nanjing University.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2020.09 - 2024.06</div>
    <div class="timeline-body"><strong>Shandong University</strong>, B.Eng. in Artificial Intelligence, School of Computer Science and Technology. Ranked 2/52 overall and awarded Outstanding Graduate of Shandong University.</div>
  </div>
</div>

<span class="anchor" id="honors"></span>

# Honors and Awards

<div class="honor-grid">
  <div class="honor-card"><span>2025</span> National Scholarship for Graduate Students</div>
  <div class="honor-card"><span>2025</span> Suzhou Niuwei Talent Award</div>
  <div class="honor-card"><span>2024</span> Shandong Provincial Government Scholarship</div>
  <div class="honor-card"><span>2024</span> Huawei Scholarship</div>
  <div class="honor-card"><span>2023</span> MCM/ICM Finalist, top 2%</div>
  <div class="honor-card"><span>2023</span> National Second Prize, Teddy Cup Data Mining Competition</div>
  <div class="honor-card"><span>2023</span> National Second Prize, Energy Conservation and Emission Reduction Competition</div>
</div>

<span class="anchor" id="skills"></span>

# Skills & Service

<ul class="compact-list">
  <li><strong>Programming:</strong> C/C++, Python/PyTorch, Linux, LaTeX.</li>
  <li><strong>Training frameworks:</strong> LLaMA Factory; VeRL (FSDP/Megatron); parameter-efficient tuning frameworks for VLMs.</li>
  <li><strong>Academic service:</strong> reviewer for ICML, IJCAI, and FCS; participated in organizing an IJCAI 2026 travel-planning workshop competition.</li>
  <li><strong>Interests:</strong> reading, table tennis, badminton, tennis, and basketball.</li>
</ul>
