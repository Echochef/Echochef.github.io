---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am **Chenhao Qiu (邱晨皓)**, currently an AI Researcher in the Foundation Model Research Group at **Mango TV**. I received my M.Eng. in Software Engineering from **Huazhong University of Science and Technology (HUST)** in 2025, and my B.Eng. in Software Engineering from **Nanchang University** in 2022.

My research interests center on **MLLM Agents**, **Agentic Reinforcement Learning**, **LLM Reasoning**, and **Long Video Understanding**. I am particularly interested in how multimodal large language models can be turned into reliable agents — closing the gap between the evidence they observe and the answers they produce. My first-author work on this question has been accepted at **ICML 2026**. <a href='https://scholar.google.com/citations?user=iZ4xW6oAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

Before joining Mango TV, I worked as an Algorithm Intern on foundation model SFT teams at **Tencent (Hunyuan)** and **Meituan (Longcat)**, where I shipped role-playing capabilities that took the Hunyuan base model to **#1 domestic / #2 overall** on the SuperClue role-playing benchmark, and contributed to large-scale alignment pipelines fine-tuning 70B+ models.

I have also been fortunate to win **7 First-Place** and **8 Second-Place** awards in major AI competitions, with cumulative prize money exceeding **$530,000**.


# 🔥 News
- *2026.05*: &nbsp;🎉 Our paper *Mitigating Evidence Misalignment in Agentic Long Video Understanding by Decoupling Answer Authority* is accepted by **ICML 2026** as a Poster.
- *2026.03*: &nbsp;🏆 Won **1st Place** at the **CVPR 2026 NTIRE Challenge** on X-AIGC Quality Assessment in Image Editing.
- *2025.09*: &nbsp;🏆 Won **1st Place** at the **ICCV 2025 Challenge** on Visual Question Answering with Spatial Awareness.
- *2025.07*: &nbsp;🚀 Started as an AI Researcher in the Foundation Model Research Group at **Mango TV**.
- *2025.06*: &nbsp;🏆 Won **1st Place** at the **Tencent Advertising Algorithm Competition** (1 / 8300+, prize ≈ $280K).

# 📝 Publications 

<div style="border-bottom:1px #efefef solid; padding:2em 0;">
  <div style="position:relative; margin-bottom:1em;">
    <div class="badge" style="position:absolute; top:8px; left:8px; z-index:2;">ICML 2026</div>
    <img src="images/icml2026_framework.jpg"
         alt="Overview of the decoupled planner–inspector framework that separates evidence retrieval from answer authority."
         style="width:100%; max-width:100%; box-shadow:3px 3px 6px #888; display:block;">
  </div>
  <div markdown="1">

[Mitigating Evidence Misalignment in Agentic Long Video Understanding by Decoupling Answer Authority](https://arxiv.org/abs/2605.12571)

**Chenhao Qiu**, Yechao Zhang, Xin Luo, Shien Song, Xusheng Liu

*The 43rd International Conference on Machine Learning (ICML 2026), Seoul, South Korea — Poster.*

- Identifies a structural bottleneck — **evidence misalignment** — in current MLLM agents for long-video QA: agents commit to answers that drift away from the visual evidence they cite.
- Proposes an **authority-decoupling** framework that separates evidence retrieval from answer generation, so the answering module no longer overrides the agent's grounded findings.
- Distilled from real-world industrial long-video pipelines and validated with extensive rigorous experiments across multiple long-video QA benchmarks.

  </div>
</div>

**Selected Manuscripts / In Progress**

- *WISDOM: Progressive Curriculum Synthesis Makes LLMs Better Mathematical Reasoners* — **Chenhao Qiu** *et al.* Submitted to ICLR 2025 (review scores 6/6/6/1). A 3-stage iterative curriculum synthesis pipeline (Weak Teacher Guiding → Critical Expert Teaching → Experts Consistency Voting); WISDOM-7B reaches 62.4% on MATH and 2/30 on AIME 2024; trained on an 88×A100 cluster.

# 🎖 Honors and Awards
**Competition record: 7 × 1st Place, 8 × 2nd Place, cumulative prizes ≈ $530,000.** Selected highlights below.

- *2026* — **1st Place**, CVPR NTIRE Challenge on X-AIGC Quality Assessment in Image Editing.
- *2025* — **1st Place**, Tencent Advertising Algorithm Competition. Rank **1 / 8300+**, prize ≈ **$280,000**.
- *2025* — **1st Place**, ICCV Challenge on Visual Question Answering with Spatial Awareness.
- *2025* — **2nd Place**, Pazhou Algorithm Competition — LLM Reasoning Optimization via PPO + PRM.
- *2024* — **1st Place**, Mango TV Large Model Competition — Logical Reasoning Track. **Team Captain**, prize ≈ **$33,000** (¥240K).
- *2024* — **1st Place**, ATEC 2024 Online Competition — Track 4.
- *2024* — **1st Place**, ATEC Challenge on Large Model Application and Security. Prize ≈ **$140,000**.
- *2023* — **1st Place**, 4th SEED Competition — Healthcare Track. **Team Captain**, prize ≈ **$11,000** (¥80K).

# 📖 Educations
- *2022.09 – 2025.06*, **M.Eng. in Software Engineering**, Huazhong University of Science and Technology (HUST), Wuhan, China.
- *2018.09 – 2022.06*, **B.Eng. in Software Engineering**, Nanchang University, Nanchang, China.

# 💼 Work Experience
- *2025.07 – Present*, **AI Researcher**, Foundation Model Research Group, **Mango TV**, Changsha.
  - **Multimodal Video Understanding:** Lead the R&D of multimodal understanding algorithms for intelligent media-asset management; built a shot-level structured parsing framework for long-form videos integrating face recognition, visual semantic modeling, and MLLMs.
  - **Independent Academic Research:** Distilled real-world industrial pipelines and SOTA literature tracking into a first-author **ICML 2026** paper on evidence misalignment in MLLM agents.
  - **Competition Organization:** Key role in the **2026 Mango TV Algorithm Competition** — task design, data construction & annotation standards, and baseline solutions. Proposal submitted to **ACM MM**.
  - **International Challenge Leadership:** Sole contributor leading the department's international competition track — **1st Place** at both ICCV 2025 Challenge and CVPR 2026 Challenge.

# 💻 Internships
- *2024.06 – 2024.09*, **Algorithm Intern**, Foundation Model SFT Team, **Tencent (Hunyuan)**, Shenzhen.
  - Optimized role-playing capabilities of the Hunyuan LLM — took the base model to **#1 domestic / #2 overall** on the SuperClue role-playing benchmark.
  - Built a data synthesis pipeline on top of the Hunyuan 7×8B MoE model; lifted the perfect-score rate from **23% → >50%** while holding the zero-score rate under 15% — **one month ahead of schedule**.
- *2024.02 – 2024.05*, **Algorithm Intern**, Foundation Model SFT Team, **Meituan (Longcat)**, Beijing.
  - Curated high-quality SFT datasets blending open-source and GPT-4-generated data; dynamically tuned mixing ratios to improve both domain-specific and general metrics.
  - Contributed to an in-house Megatron-based distributed training framework — **4× training speedup**; fine-tuned Qwen1.5-72B, Yi-34B, Llama2-70B.
  - Built an RLHF pipeline (DPO, PPO) on top of SFT models and a robust bad-case analysis loop for continuous iteration.

# 🛠 Skills & Interests
- **AI-assisted Engineering** — daily user of Claude / Codex for prototyping, refactoring, and full-system development; pair coding with careful design, testing, and engineering discipline.
- **Full-stack independent projects** — designed, built, and shipped *PaperAgent* end-to-end (algorithmic pipeline, backend, database, iOS client) for AI-assisted paper retrieval, citation mining, and personalized daily literature recommendations.
- **Beyond research** — long-distance solo travel; it has sharpened my independence, adaptability, and problem-solving in unfamiliar environments.

# 📫 Contact
- Email: [1226309312qch@gmail.com](mailto:1226309312qch@gmail.com)
- GitHub: [github.com/Echochef](https://github.com/Echochef)
- Google Scholar: [Chenhao Qiu](https://scholar.google.com/citations?user=iZ4xW6oAAAAJ)
