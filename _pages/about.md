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

Welcome! I'm Junjie HUANG, a Ph.D. candidate at the Chinese University of Hong Kong, advised by [Prof. Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/). I am currently a Research Intern at **ByteDance Seed**, mentored by [Dr. Wanjun Zhong](https://zhongwanjun.github.io/). Previously, I received my Bachelor's degree in 2020 and Master's degree in 2023 from Beihang University, advised by [Prof. Ke Xu](https://scse.buaa.edu.cn/info/1078/2655.htm).

I am currently working on **general agents**, building strong *agent harness* and training general *agentic LLM*. Besides, I am also interested in **code agents**. Discussions and collaborations are warmly welcomed!

> 🚀 <span style="color:red">**I will be on the industry job market this year (expected to graduate in 2027).**</span> Feel free to reach out at my email/wechat (**id: junjieh9**) if you would like to share opportunities, collaborate, or just chat :)

#### Highlights 

- **Agent Foundation Model** (@ ByteDance Seed)
  - Agent Foundation Models: improving the *MCP tool-use* ability of [**Seed 2.0**](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf), evaluated on **MCPMark**, **BFCL**, and **τ-bench**.
  - Environment Synthesis: scaling real-world environments for evolving general agent intelligence with [**Agent-World**](https://agent-tars-world.github.io/) (2,000+ environments, 19K+ tools, 23 benchmarks).
  - General Agent: improving end-to-end *task-completion* ability of agents, deployed as [**Doubao Super Mode 豆包超能模式**](https://www.doubao.com/super-task-apply).
- **AI for Code and Software Engineering** (Ph.D.)
  - Code Intelligence: [CodeXGLUE](https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/file/c16a5320fa475530d9583c34fd356ef5-Paper-round1.pdf) (NeurIPS 2021), [CoSQA](https://aclanthology.org/2021.acl-long.442.pdf) (ACL 2021), [CoCoNote](/assets/papers/ase24_coconote.pdf) (ASE 2024)
  - LLM for Software Engineering: [iKnow](/assets/papers/ase25_iknow.pdf) (ASE 2025, 🏆 <span style="color:red">*ACM SIGSOFT Distinguished Paper*</span>), [CodeAD](https://arxiv.org/pdf/2510.22986) (arXiv 2025), [LUNAR](/assets/papers/fse25_lunar.pdf) (FSE 2025), [LoFI](/assets/papers/issre24_lofi.pdf) (ISSRE 2024), [FaultProfIT](/assets/papers/icseseip24_faultprofit.pdf) (ICSE-SEIP 2024)
  - MLSys: [PreServe](https://www.zhihan-jiang.com/files/ICSE26/PreServe.pdf) (ICSE 2026, 🏆 <span style="color:red">*ACM SIGSOFT Distinguished Paper*</span>), [L4](https://arxiv.org/pdf/2503.20263) (FSE 2025)

{% include_relative news.md %}

{% include_relative pub.md %}


# 🏃 Experiences
- *2025.12 - Present*: Research Intern, Agent Post-Training Team at **ByteDance Seed**. Mentors: [Dr. Wanjun Zhong](https://zhongwanjun.github.io/).
- *2020.06 - 2022.06*: Research Intern, NLC at Microsoft Research Asia, Mentor: [Dr. Nan Duan](https://nanduan.github.io/).
- *2020.05 - 2021.06*: Research Intern, NLC at Microsoft Research Asia, Mentor: [Dr. Duyu Tang](https://scholar.google.com/citations?user=9uz-D-kAAAAJ).
- *2018.09 - 2020.04*: Research Assistant, NLP Lab at Tsinghua University, Advisor: [Prof. Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/).

# 🎖 Honors and Awards
- *2026* 🏆 **ACM SIGSOFT Distinguished Paper Award**, ICSE'26 (for *PreServe*)
- *2025* 🏆 **ACM SIGSOFT Distinguished Paper Award**, ASE'25 (for *iKnow*)
- *2023-2027* **CUHK Vice-Chancellor's PhD Scholarship**, The Chinese University of Hong Kong
- *2020-2021* **National Scholarship**, Ministry of Education of the P.R. China
- *2017-2018* **National Scholarship**, Ministry of Education of the P.R. China
- *2019* **Yuanhang Scholarship**, Beihang University

# 💻 Activities
- [代码智能新基准数据集CodeXGLUE来袭，多角度衡量模型优劣](https://www.msra.cn/zh-cn/news/features/codexglue)
- [北航第四届驭远杯机器人大赛--全自动目标识别及抓取机器人](https://www.bilibili.com/video/BV1sU4y1A7wa/?vd_source=ddb3c65c685b436fa9a63a347a681efe)

# 💼 Services

- Program Committee:
  - 2025: APSEC'25
- Sub-Reviewer:
  - 2025: ICSE, ISSTA, DSN, ASE, FSE
  - 2024: FSE, ISSTA, ISSRE
  - 2023: FSE, DSN

# 📞 Contact

Please feel free to contact me via my email (left) if you are interested in our papers, my experience, or you just have any problem on research which I may help. 
