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

I am **Song-Lin Lv** (吕松霖), a master's student in Computer Science and Technology at the School of Intelligence Science and Technology, **Nanjing University**. I am advised by Prof. [Lan-Zhe Guo](https://www.lamda.nju.edu.cn/guolz/) and work with [LAMDA](https://www.lamda.nju.edu.cn/), led by Prof. [Zhi-Hua Zhou](https://cs.nju.edu.cn/zhouzh/). Before that, I received my B.Eng. in Artificial Intelligence from **Shandong University**.

<div class="research-interests" aria-label="Research interests">
  <div class="interest-label">Research Interests</div>
  <div class="interest-list">
    <span class="interest-tag interest-tag--llm">LLM/MLLM Post-training</span>
    <span class="interest-tag interest-tag--rl">Reinforcement Learning</span>
    <span class="interest-tag interest-tag--vlm">Vision-Language Models</span>
    <span class="interest-tag interest-tag--agent">Agentic AI</span>
  </div>
</div>

My current research centers on post-training large language models and multimodal large language models, including supervised fine-tuning, reinforcement learning, rubric-guided reward design, model distillation, and test-time performance improvement. I am also interested in reliable vision-language learning, especially parameter-efficient tuning, calibration, and semi-supervised self-training.

<span class="anchor" id="news"></span>

# News

<ul class="news-list">
  <li class="news-item">
    <span class="news-date">2026.04</span>
    <span class="news-body">I joined Douyin AI Search at ByteDance as an LLM algorithm intern, working on Rubric RL and post-training for AI search QA.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.08</span>
    <span class="news-body"><em>BMIP</em> was accepted by <strong>IJCAI 2025</strong> as an <strong>Oral</strong> paper.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.07</span>
    <span class="news-body">I joined Huawei Terminal BG as an AI algorithm intern, focusing on multimodal tool-use reinforcement learning.</span>
  </li>
</ul>

<span class="anchor" id="publications"></span>

# Publications

<sup>*</sup> denotes equal contribution. Selected manuscripts are listed below.

<section class="publication-section">
<h2>Conference Papers</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2025</span>
      <span class="paper-note award">Oral</span>
    </div>
    <h3><a href="https://www.ijcai.org/proceedings/2025/655">BMIP: Bi-directional Modality Interaction Prompt Learning for VLM</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--tuning">Prompt Learning</span></div>
    <p>We propose a parameter-efficient prompt-learning framework for CLIP-style vision-language models. BMIP learns visual and textual prompts independently while enabling bidirectional modality interaction through attention-weighted prompt exchange.</p>
    <p class="pub-links"><a href="https://www.ijcai.org/proceedings/2025/655">Paper</a></p>
  </article>
</div>
</section>

<section class="publication-section">
<h2>Preprints &amp; Under Review</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">ICML 2026</span>
      <span class="paper-note">To Appear</span>
    </div>
    <h3>Can Agents Generalize to the Open World? Unveiling the Fragility of Static Training in Tool Use</h3>
    <p class="authors">Equal contribution, presenting author.</p>
    <div class="paper-interests"><span class="interest-tag--agent">LLM Agents</span><span class="interest-tag--rl">LLM RL</span></div>
    <p>We study whether post-trained tool-use agents can adapt to open-world changes such as out-of-distribution tasks, updated tool names, domain shifts, and unexpected tool errors. The work compares SFT, RL, and SFT+RL pipelines and proposes Perturbation-Augmented Fine-Tuning (PAFT) to improve robustness.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">AAAI 2027</span>
      <span class="paper-note">In Preparation</span>
    </div>
    <h3>Counterfactual Replay for Token-Level Rubric-Guided Policy Optimization</h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--rl">LLM RL</span><span class="interest-tag--distill">Distillation</span></div>
    <p>We explore token-level credit assignment for Rubric RL. The method uses counterfactual replay to compare teacher and student likelihoods at the token level, then reweights GRPO advantages without requiring an extra reward model or changing sequence-level rewards.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">AAAI 2027</span>
      <span class="paper-note">In Preparation</span>
    </div>
    <h3>Perception-Inference Decoupling: A Dual-Stage Framework to Boost LVLM Reasoning</h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">MLLM</span><span class="interest-tag--reasoning">Reasoning</span></div>
    <p>We investigate hallucination in multimodal large language models by explicitly separating visual perception from reasoning, and optimize the two stages to improve multimodal understanding and inference.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">EMNLP 2026</span>
      <span class="paper-note">Under Review</span>
    </div>
    <h3>HyPRM: A Hybrid Process Reward Model for Pre-Execution Action Selection in Multimodal Agents</h3>
    <p class="authors">Equal contribution, mentor.</p>
    <div class="paper-interests"><span class="interest-tag--agent">Multimodal Agents</span><span class="interest-tag--rl">Reward Models</span></div>
    <p>We train a process reward model from optimal and redundant tool-use chains to reduce unnecessary tool calls in multimodal agents, supporting both RL reward design and test-time action selection.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2026</span>
      <span class="paper-note award">Oral</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2510.20477">Bi-CoG: Bi-Consistency-Guided Self-Training for Vision-Language Models</a></h3>
    <p class="authors">Equal contribution.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--ssl">Semi-Supervised Learning</span></div>
    <p>Bi-CoG combines multiple VLMs as base classifiers and uses their original generalization ability for multi-view self-training on unlabeled data, targeting open-environment and VLM evaluation settings.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2510.20477">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">WAICA 2026</span>
      <span class="paper-note">Under Review</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2505.13317">Unlabeled Data or Pre-trained Model: Rethinking Semi-Supervised Learning and Pretrain-Finetuning</a></h3>
    <p class="authors">Equal contribution.</p>
    <div class="paper-interests"><span class="interest-tag--ssl">Semi-Supervised Learning</span><span class="interest-tag--vlm">Pretrain-Finetuning</span></div>
    <p>We compare semi-supervised learning and pretrain-finetuning under data scarcity, summarizing their strengths and motivating future hybrid algorithms.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2505.13317">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">AAAI 2027</span>
      <span class="paper-note">In Preparation</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2501.19060">Shift-Aware Calibration for Fine-Tuned CLIP: Leveraging Image-Text Alignment</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--calibration">Calibration</span></div>
    <p>We leverage the calibration behavior of original CLIP to improve confidence estimation after fine-tuning, aiming to make deployed VLMs more reliable under distribution shift.</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2501.19060">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">TPAMI</span>
      <span class="paper-note">Under Review</span>
    </div>
    <h3>DECOOP: Robust Prompt Tuning with Out-of-Distribution Detection</h3>
    <p class="authors">Second author.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Prompt Learning</span><span class="interest-tag--ood">OOD Detection</span></div>
    <p>DECOOP improves CLIP prompt tuning in open environments by combining multiple sub-experts with a general expert and deciding when to fall back to the general expert under uncertainty.</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">Benchmark</span>
    </div>
    <h3>OpenPL: Realistic Evaluation of Prompt Learning for VLM in Open Environments</h3>
    <p class="authors">Second author.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">Vision-Language Models</span><span class="interest-tag--benchmark">Benchmark</span></div>
    <p>OpenPL systematically evaluates pretrained vision-language models under realistic open-environment shifts, including category changes and distribution shifts, and analyzes limitations of existing prompt-tuning methods.</p>
  </article>
</div>
</section>

<span class="anchor" id="experience"></span>

# Experience

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026.04 - Present</div>
    <div class="timeline-body"><strong>LLM Algorithm Intern</strong>, Douyin AI Search, ByteDance, Shanghai. Working on Rubric RL, large-scale RL/OPD post-training, reward design for answer style, DCPO prior reward optimization, and dynamic sampling for efficient post-training.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.07 - 2025.10</div>
    <div class="timeline-body"><strong>AI Algorithm Intern</strong>, Huawei Terminal BG, Xiaoyi Cloud Service, Shanghai. Built a reinforcement-learning post-training pipeline for Qwen-32B-VL tool use and improved answer accuracy for the Xiaoyi assistant.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">Project Internship</div>
    <div class="timeline-body"><strong>National Project Internship</strong>, SAC algorithm deployment. Participated in an on-site project in Beijing and deployed calibration algorithms for confidence-sensitive classification scenarios.</div>
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

# Skills &amp; Service

<ul class="compact-list">
  <li><strong>Programming:</strong> C/C++, Python/PyTorch, Linux, LaTeX.</li>
  <li><strong>Training frameworks:</strong> LLaMA Factory; VeRL (FSDP/Megatron); parameter-efficient tuning frameworks for VLMs.</li>
  <li><strong>Academic service:</strong> reviewer for ICML, IJCAI, and FCS; participated in organizing an IJCAI 2026 travel-planning workshop competition.</li>
  <li><strong>Interests:</strong> reading, table tennis, badminton, tennis, and basketball.</li>
</ul>
