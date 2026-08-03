---
permalink: /
title: ""
excerpt: "吕松霖，南京大学计算机科学与技术硕士研究生，研究方向包括大语言模型/多模态大模型后训练、强化学习与视觉语言模型。"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

我是 **吕松霖**（Song-Lin Lv），南京大学智能科学与技术学院计算机科学与技术专业硕士研究生，导师为 [郭兰哲](https://www.lamda.nju.edu.cn/guolz/) 助理教授，目前在 [LAMDA](https://www.lamda.nju.edu.cn/) 课题组学习与研究。此前，我于山东大学计算机科学与技术学院获得人工智能专业工学学士学位。

<div class="research-interests" aria-label="研究方向">
  <div class="interest-label">研究方向</div>
  <div class="interest-list">
    <span class="interest-tag interest-tag--llm">大语言模型/多模态大模型后训练</span>
    <span class="interest-tag interest-tag--rl">强化学习</span>
    <span class="interest-tag interest-tag--vlm">视觉语言模型</span>
    <span class="interest-tag interest-tag--agent">Agentic AI</span>
  </div>
</div>

我的研究以大语言模型（LLM）与多模态大语言模型（MLLM）的后训练为主，关注监督微调、强化学习、Rubric-guided reward 设计、模型蒸馏与测试时间性能提升等问题。同时，我也长期关注视觉语言模型的可靠学习，包括参数高效微调、置信度校准与半监督自训练等方向。

<span class="anchor" id="news"></span>

# 近期动态

<ul class="news-list">
  <li class="news-item">
    <span class="news-date">2026.07</span>
    <span class="news-body"><em><a href="https://arxiv.org/abs/2607.25659">CoRT</a></em> 发布在 arXiv，研究 Rubric-guided GRPO 中的 token 级信用分配问题。</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026</span>
    <span class="news-body">开放世界工具调用 Agent 泛化能力相关工作被 <strong>ICML 2026</strong> 接收。</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026</span>
    <span class="news-body"><em>Bi-CoG</em> 被 <strong>IJCAI 2026</strong> 接收为 <strong>Oral</strong> 论文。</span>
  </li>
  <li class="news-item">
    <span class="news-date">2026.04</span>
    <span class="news-body">加入字节跳动抖音 AI 搜索，担任大模型算法实习生，参与 AI 搜索问答卡模型的 Rubric RL 与后训练优化。</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.08</span>
    <span class="news-body"><em>BMIP</em> 被 <strong>IJCAI 2025</strong> 接收为 <strong>Oral</strong> 论文。</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025.07</span>
    <span class="news-body">加入华为终端 BG 小艺云服务部，担任 AI 算法实习生，参与多模态工具调用强化学习训练。</span>
  </li>
</ul>

<span class="anchor" id="publications"></span>

# 论文与研究

<sup>*</sup> 表示共同一作。以下列出部分代表性工作。为避免影响双盲评审，尚未公开接收的在投/准备中工作仅保留通用状态，不标注目标会议或期刊。

<section class="publication-section">
<h2>已发表 / 已接收</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2025</span>
      <span class="paper-note award">Oral</span>
    </div>
    <h3><a href="https://www.ijcai.org/proceedings/2025/655">BMIP: Bi-directional Modality Interaction Prompt Learning for VLM</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">视觉语言模型</span><span class="interest-tag--tuning">提示学习</span></div>
    <p>提出一种面向 CLIP 类视觉语言模型的参数高效提示学习框架，在视觉模态与语言模态分别学习提示参数，并通过双向模态交互机制实现提示间的信息传递，从而提升下游任务特征表示能力。</p>
    <p class="pub-links"><a href="https://www.ijcai.org/proceedings/2025/655">Paper</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">IJCAI 2026</span>
      <span class="paper-note award">Oral</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2510.20477">Bi-CoG: Bi-Consistency-Guided Self-Training for Vision-Language Models</a></h3>
    <p class="authors">共同一作。</p>
    <div class="paper-interests"><span class="interest-tag--vlm">视觉语言模型</span><span class="interest-tag--ssl">半监督学习</span></div>
    <p>结合多种 VLM 的原始泛化能力进行多视图无标注数据自训练，在开放环境设置与 VLM 评估设置中提升半监督学习表现。</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2510.20477">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">已接收</span>
    </div>
    <h3>Can Agents Generalize to the Open World? Unveiling the Fragility of Static Training in Tool Use</h3>
    <p class="authors">共同一作，参会作者。</p>
    <div class="paper-interests"><span class="interest-tag--agent">LLM Agents</span><span class="interest-tag--rl">LLM RL</span></div>
    <p>研究后训练工具调用 Agent 在开放世界变化下的泛化能力，包括分布外任务、工具名称更新、领域迁移与工具突发错误等场景。工作系统比较 SFT、RL 与 SFT+RL 等训练流程，并提出 Perturbation-Augmented Fine-Tuning（PAFT）以增强模型鲁棒性。</p>
  </article>
</div>
</section>

<section class="publication-section">
<h2>预印本 / 进行中</h2>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">arXiv 2026</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2607.25659">CoRT: Counterfactual Replay for Token-Level Rubric-Guided Policy Optimization</a></h3>
    <p class="authors">Bo-Wen Zhang, Junwei He, Wen Wang, <strong>Song-Lin Lv</strong>, Wentao Ma, Rongyi Lin, Shuhan Zhong, Lan-Zhe Guo.</p>
    <div class="paper-interests"><span class="interest-tag--rl">LLM RL</span><span class="interest-tag--distill">蒸馏</span></div>
    <p>探索 Rubric RL 中的 token 级信用分配问题。CoRT 通过反事实回放比较有无 rubric 条件下同一回答的 token 级似然差异，并据此重分配 GRPO 优势值，无需额外 token 打分模型且不改变原始序列奖励。</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2607.25659">arXiv</a> / <a href="https://arxiv.org/pdf/2607.25659">PDF</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">进行中</span>
    </div>
    <h3>Perception-Inference Decoupling: A Dual-Stage Framework to Boost LVLM Reasoning</h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">MLLM</span><span class="interest-tag--reasoning">推理</span></div>
    <p>针对多模态大语言模型中的图像感知幻觉与推理幻觉，研究显式分离感知与推理过程的两阶段优化策略，以提升模型的多模态理解与推理能力。</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">在投</span>
    </div>
    <h3>HyPRM: A Hybrid Process Reward Model for Pre-Execution Action Selection in Multimodal Agents</h3>
    <p class="authors">共同一作，指导者。</p>
    <div class="paper-interests"><span class="interest-tag--agent">多模态 Agent</span><span class="interest-tag--rl">过程奖励模型</span></div>
    <p>通过构建理想工具调用链条与冗余工具链条训练过程奖励模型，用于强化学习奖励设计与测试时工具选择，以减少结果导向奖励带来的工具调用冗余问题。</p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">在投</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2505.13317">Unlabeled Data or Pre-trained Model: Rethinking Semi-Supervised Learning and Pretrain-Finetuning</a></h3>
    <p class="authors">共同一作。</p>
    <div class="paper-interests"><span class="interest-tag--ssl">半监督学习</span><span class="interest-tag--vlm">预训练-微调</span></div>
    <p>比较半监督学习与预训练-微调范式在标注数据稀缺场景下的表现，总结两类方法的优势与局限，并为后续融合算法提供参考。</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2505.13317">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">进行中</span>
    </div>
    <h3><a href="https://arxiv.org/abs/2501.19060">Shift-Aware Calibration for Fine-Tuned CLIP: Leveraging Image-Text Alignment</a></h3>
    <p class="authors"><strong>Song-Lin Lv</strong>, coauthors.</p>
    <div class="paper-interests"><span class="interest-tag--vlm">视觉语言模型</span><span class="interest-tag--calibration">置信度校准</span></div>
    <p>利用原始 CLIP 良好的校准特性改善微调后模型的置信度估计，使 VLM 在分布偏移下更加可靠、可部署。</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2501.19060">arXiv</a></p>
  </article>

  <article class="publication-item">
    <div class="publication-meta">
      <span class="venue-badge">在投</span>
    </div>
    <h3>DECOOP: Robust Prompt Tuning with Out-of-Distribution Detection</h3>
    <p class="authors">第二作者。</p>
    <div class="paper-interests"><span class="interest-tag--vlm">提示学习</span><span class="interest-tag--ood">OOD 检测</span></div>
    <p>面向开放环境中的 CLIP 提示微调问题，通过多个子专家与通用专家协同工作，并在不确定时回退至通用专家，从而提升模型的开放环境鲁棒性。</p>
  </article>
</div>
</section>

<span class="anchor" id="experience"></span>

# 经历

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026.04 - 至今</div>
    <div class="timeline-body"><strong>大模型算法实习生</strong>，字节跳动抖音 AI 搜索，上海。</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.07 - 2025.10</div>
    <div class="timeline-body"><strong>AI 算法实习生</strong>，华为终端 BG 小艺云服务部，上海。</div>
  </div>
</div>

<span class="anchor" id="education"></span>

# 教育经历

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2024.09 - 2027.06</div>
    <div class="timeline-body"><strong>南京大学</strong>，计算机科学与技术硕士，智能科学与技术学院。导师：<a href="https://www.lamda.nju.edu.cn/guolz/">郭兰哲</a> 助理教授；课题组：LAMDA。曾获南京大学优秀研究生。</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2020.09 - 2024.06</div>
    <div class="timeline-body"><strong>山东大学</strong>，人工智能本科，计算机科学与技术学院。综合排名 2/52，获山东大学优秀毕业生。</div>
  </div>
</div>

<span class="anchor" id="honors"></span>

# 荣誉奖项

<div class="honor-grid">
  <div class="honor-card"><span>2025</span> 研究生国家奖学金</div>
  <div class="honor-card"><span>2025</span> 苏州市牛尾英才奖</div>
  <div class="honor-card"><span>2024</span> 山东省政府奖学金</div>
  <div class="honor-card"><span>2024</span> 华为奖学金</div>
  <div class="honor-card"><span>2023</span> 美国大学生数学建模竞赛特等奖提名，前 2%</div>
  <div class="honor-card"><span>2023</span> 泰迪杯数据挖掘竞赛国家级二等奖</div>
  <div class="honor-card"><span>2023</span> 全国大学生节能减排科技竞赛国家级二等奖</div>
</div>

<span class="anchor" id="skills"></span>

# 技能与服务

<ul class="compact-list">
  <li><strong>编程：</strong>C/C++、Python/PyTorch、Linux、LaTeX。</li>
  <li><strong>训练框架：</strong>LLaMA Factory；VeRL（FSDP/Megatron）；视觉语言编码模型参数高效微调训练框架。</li>
  <li><strong>学术服务：</strong>担任 ICML、IJCAI、FCS 等会议/期刊审稿人；参与 IJCAI 2026 旅行规划 Workshop 竞赛组织。</li>
  <li><strong>兴趣爱好：</strong>阅读、乒乓球、羽毛球、网球、篮球。</li>
</ul>
