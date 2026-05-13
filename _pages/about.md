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

Hello, I am Jiahao Yuan, currently studying Artificial Intelligence at <a href="https://www.ecnu.edu.cn/">East China Normal University (ECNU)</a>. I received my bachelor’s degree in Computer Science and Technology from <a href="https://www.usst.edu.cn/">University of Shanghai for Science and Technology (USST)</a>.

My research interests broadly lie in **enhancing reasoning capabilities of LLMs/MLLMs through post-training and agent rl, and aligning model capabilities across tasks and behaviors** robustly in complex real-world environments. My long-term goal is to develop reasoning alignment and social alignment AI systems that benefit society. 
I have published 7 papers in top international AI conferences such as ACL, AAAI, WWW, and MM, including associated competitions. I am also excited to announce the release of our newest empathetic large language model, Kardia-R1.
As the lead contributor and first author during my internship at Ant Group , I represented the team in releasing **2 technical reports**: [Query as Anchor](https://arxiv.org/abs/2602.14492) & [How do decoder-only llm perceive user?](https://arxiv.org/abs/2602.10622).
I am currently seeking job opportunities related to large language models.

Feel free to reach out via email at [jamse_yuan@163.com](mailto:jamse_yuan@163.com) 🤗 for relevant opportunities or potential collaborations —— I’m always open to research discussions!

# 🔥 News
- 2026.03: &nbsp;🎉🎉 Our Altas accepted to ACL 2026 Finding !!! Congratulations to Wu !

- 2026.02: &nbsp;🎉🎉 Completed my 6‑month internship at Ant Group (ended Jan 2026) and published two technical reports ([Query as Anchor](https://arxiv.org/abs/2602.14492) & [How do decoder-only llm perceive user?](https://arxiv.org/abs/2602.10622)). Special thanks to the DeepFind team!

- 2026.01: &nbsp;🎉🎉 Our Kardia-R1 accepted to WWW 2026 !!!

- 2025.11: &nbsp;🎉🎉 One paper accepted to AAAI 2026 !!!
 
- 2025.07: &nbsp;🎉🎉 One paper accepted to ACM Multimedia 2025 !!!

- 2025.05: &nbsp;🎉🎉 Two papers accepted to ACL 2025 Main Conference !!!

- 2025.05: &nbsp;🎉🎉 Achieved 3rd place 🏆 in the XLLM@ACL2025 Shared Task-III: LLM for Structural Reasoning!

- *Ongoing* 🛠️ **Maintainer**, [Awesome-LLM-Empathy](https://github.com/JhCircle/Awesome-LLM-Empathy) — a curated list of LLM resources for empathy and affective computing ![GitHub Repo stars](https://img.shields.io/github/stars/JhCircle/Awesome-LLM-Empathy?style=social)

# 📝 Publications (* Indicates Equal Contribution, † Indicates Project Leader)

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">Tech Report</div><img src='./images/Deepfind-GGSM.png' alt="ggsm" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[How Do Decoder-Only LLMs Perceive Users? Rethinking Attention Masking for User Representation Learning](https://arxiv.org/abs/2602.10622)

**Jiahao Yuan †**, Yike Xu, Jinyong Wen, Baokun Wang, Yang Chen, Xiaotong Lin, Wuliang Huang, Ziyi Gao, Xing Fu, Yu Cheng, Weiqiang Wang

Tech Report (Ant Group) | [Code](https://github.com/JhCircle/Deepfind-GGSM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">Tech Report</div><img src='./images/Query-as-Anchor.png' alt="q-anchor" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Query-as-Anchor: Scenario-Adaptive User Representation via Large Language Model](https://arxiv.org/abs/2602.14492)

**Jiahao Yuan †**, Yike Xu, Jinyong Wen, Baokun Wang, Ziyi Gao, Xiaotong Lin, Yun Liu, Xing Fu, Yu Cheng, Yongchao Liu, Weiqiang Wang, Zhongle Xie

Tech Report (Ant Group) | [Code](https://github.com/JhCircle/Q-Anchor)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">WWW 2026</div><img src='./images/Kardia-R1.png' alt="kardia" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Kardia-R1: Unleashing LLMs to Reason toward Understanding and Empathy for Emotional Support via Rubric-as-Judge Reinforcement Learning](https://arxiv.org/abs/2512.01282)

**Jiahao Yuan †**, Zhiqing Cui, Hanqing Wang, Yuansheng Gao, Yucheng Zhou, Usman Naseem

WWW 2026 | [Code](https://github.com/JhCircle/Kardia-R1)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">Arxiv</div><img src='./images/CulturalPalette.png' alt="culturalpalette" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Cultural Palette: Pluralising Culture Alignment via Multi-agent Palette](https://arxiv.org/abs/2412.11167)

**Jiahao Yuan**, Zixiang Di, Shangzixin Zhao, Zhiqing Cui, Hanqing Wang, Guisong Yang, Usman Naseem

Under Review
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">Arxiv</div><img src='./images/Prune_on_Logic.png' alt="Prune_on_Logic" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Can Pruning Improve Reasoning? Revisiting Long-CoT Compression with Capability in Mind for Better Reasoning](https://arxiv.org/abs/2505.14582)

Shangziqi Zhao\*, **Jiahao Yuan\* †**, Jinyang Wu\*, Zhenglin Wang, Guisong Yang, Usman Naseem

Under Review | [Code](https://github.com/JhCircle/Kardia-R1)
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div style="text-align: center;">
<div class="badge">MM 2025</div><img src='./images/Draw_with_Thought.png' alt="draw" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Draw with Thought: Unleashing Multimodal Reasoning for Scientific Diagram Generation](https://arxiv.org/abs/2504.09479)

Zhiqing Cui\*, **Jiahao Yuan\***, Hanqing Wang, Yanshu Li, Chenxu Du, Zhenglong Ding

ACM MM 2025 Oral 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">ACL 2025</div><img src='./images/RoT.png' alt="rot" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reversal of Thought: Enhancing Large Language Models with Preference-Guided Reverse Reasoning Warm-up](https://aclanthology.org/2025.acl-long.955/)

**Jiahao Yuan**, Dehui Du, Hao Zhang, Zixiang Di, Usman Naseem

ACL 2025 Main | [Code](https://github.com/RoT-llm/Reversal-of-Thought)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">ACL 2025</div><img src='./images/ReflectDiffu.png' alt="reflectdiffu" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReflectDiffu:Reflect between Emotion-intent Contagion and Mimicry for Empathetic Response Generation via a RL-Diffusion Framework](https://aclanthology.org/2025.acl-long.1235/)

**Jiahao Yuan**, Zixiang Di, Zhiqing Cui, Guisong Yang, Usman Naseem

ACL 2025 Main
</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">LLMSR@XLLM25</div>
      <img src='images/less_is_more.png' alt="sym" style="display: inline-block; width: 40%;">
    </div>
  </div>

<div class='paper-box-text' markdown="1">

[LLMSR@XLLM25: Less is More: Enhancing Structured Multi-Agent Reasoning via Quality-Guided Distillation](https://aclanthology.org/2025.xllm-1.23/)

**Jiahao Yuan**, Xingzhe Sun, Xing Yu, Jingwen Wang, Dehui Du, Zhiqing Cui, Zixiang Di

XLLM@ACL (Challenge, 3rd Place) 2025 | [Code](https://github.com/JhCircle/Less-is-More)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><div class="badge">AAAI 2026</div><img src='./images/affr1.png' alt="affr1" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Affordance-R1: Reinforcement Learning for Generalizable Affordance Reasoning in Multimodal Large Language Model](https://arxiv.org/abs/2508.06206)

Hanqing Wang, Shaoyang Wang, Yiming Zhong, Zemin Yang, Jiamin Wang, Zhiqing Cui, **Jiahao Yuan**, Yifan Han, Mingyu Liu, Yuexin Ma
AAAI 2026 Oral
</div>
</div>

## Other Paper
- [Uno-Orchestra: Parsimonious Agent Routing via Selective Delegation](https://arxiv.org/abs/2605.05007) Zhiqing Cui\*, Haotong Xie\*, **Jiahao Yuan**, Cheng Yang, Hanqing Wang, Yuxin Wu, Yifan Wu, Siru Zhong, Tao Yu, Yifu Guo, Siyu Zhang, Xinlei Yu, Qibing Ren, Usman Naseem
- [(ACL 2026 Finding) ATLAS: Orchestrating Heterogeneous Models and Tools for Multi-Domain Complex Reasoning](https://arxiv.org/abs/2601.03872) Jinyang Wu\*, Guocheng Zhai\*, Ruihan Jin\*, **Jiahao Yuan**, Yuhao Shen, Shuai Zhang, Zhengqi Wen, Jianhua Tao
- [Draw ALL Your Imagine: A Holistic Benchmark and Agent Framework for Complex Instruction-based Image Generation](https://arxiv.org/abs/2505.24787) Yucheng Zhou, **Jiahao Yuan**, Qianning Wang
- [Instruction-aware User Embedding via Synergistic Language and Representation Modeling](https://arxiv.org/abs/2510.11016) Ziyi Gao\*, Yike Xu\*, **Jiahao Yuan**, Baokun Wang, Jinyong Wen, Xiaotong Lin, Yun Liu, Xing Fu, Yu Cheng, Yongchao Liu, Weiqiang Wang, Zhongle Xie

# 🎖 Honors and Awards
- *2023–2024* First-Class Scholarship for Academic Excellence in USST
- *2023* IoT Track, Chinese Collegiate Computing Competition, **First Prize**
- *2023* Software Application Development Track, Chinese Collegiate Computing Competition, **Third Prize**
- *2023* China Collegiate Computing Contest-Network Technology Challenge, **Third Prize**
- *2022–2023* First-Class Scholarship for Academic Excellence in USST
- *2021–2022* Outstanding Student in USST
- *2020–2021* First-Class Scholarship for Academic Excellence in USST

# 📖 Educations
- *2024.06 - now*, Artificial Intelligence, East China Normal University. 
- *2020.09 - 2024.06*, Computer Science & Technology, University of Shanghai for Science and Technology. 

# ✍️ Service

- Reviewer: ACL (2025-2026); EMNLP (2025-2026); AAAI (2026); WWW (2025-2026); KDD (2026); IJCAI (2025)

# 💻 Internships
- 2024.07-2024.11, ByteDance, Living Services Department – User Growth Algorithm Intern
- 2025.06-2026.01, Ant Group, User Understanding and Representation Large Model Research Intern
- 2026.01-2026.04, ByteDance, Douyin Group ,Content Understanding LLM Byteintern

<div style="text-align: center;">
  <div style="display: inline-block; width: 40%;">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=YWgGoIlggZYg6Cy3hc4bQ4St11CqzFdCMlhV_VhsJBQ&cl=ffffff&w=a"></script>
</div>
</div>

