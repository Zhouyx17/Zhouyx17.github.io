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

I am currently a fourth-year PhD student in the Department of Electronic Engineering at Tsinghua University, supervised by Professor Wu Ji. I also received my Bachelor degree from the Department of Electronic Engineering at Tsinghua University. I am currently an intern researcher at iFLYTEK.

My research interest includes evaluation and knowledge injection for large language models. I have published 4 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=RxWuu7gAAAAJ'>google scholar citations <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2024.04*: Our paper *MultifacetEval: Multifaceted Evaluation to Probe LLMs in Mastering Medical Knowledge* has been accepted by **the Thirty-Third International Joint Conference on Artificial Intelligence (IJCAI-24)**. Codes and Datasets are available [here](https://github.com/Zhouyx17/MultifacetEval).

# 📝 Publications 


- [THiFly_Queens at SemEval-2021 Task 9: Two-stage Statement Verification with Adaptive Ensembling and Slot-based Operation](https://aclanthology.org/2021.semeval-1.50.pdf), **Yuxuan Zhou**, Kaiyin Zhou, Xien Liu, Ji Wu, Xiaodan Zhu, **SemEval 2021**.
- [Table-based fact verification with self-adaptive mixture of experts](https://aclanthology.org/2022.findings-acl.13.pdf), **Yuxuan Zhou**, Xien Liu, Kaiyin Zhou, Ji Wu, **Findings of ACL 2022**.
- [THiFLY Research at SemEval-2023 Task 7: A Multi-granularity System for CTR-based Textual Entailment and Evidence Retrieval](https://aclanthology.org/2023.semeval-1.234.pdf), **Yuxuan Zhou**, Ziyu Jin, Meiwei Li, Miao Li, Xien Liu, Xinxin You, Ji Wu, **SemEval 2023**.
- [MultifacetEval: Multifaceted Evaluation to Probe LLMs in Mastering Medical Knowledge](https://www.ijcai.org/proceedings/2024/0737.pdf), **Yuxuan Zhou**, Xien Liu, Chen Ning, Ji Wu, **IJCAI 2024** (12 Min Oral).
- Reliable and diverse evaluation of LLM medical knowledge mastery, **Yuxuan Zhou**, Xien Liu, Chen Ning, Ji Wu, Preprint.

# 🎖 Honors and Awards
- *2022-2023* Tsinghua Alumni - Pinghu Talents Scholarship (Second Class). 
- *2023-2024* Tsinghua Alumni - Quanzhou Talents Scholarship (Second Class).
- *2024-2025* Tsinghua Alumni - Jining Talents Scholarship (Second Class). 

# 📖 Educations
- *2021.08 - Present*, PhD Student, Department of Electronic Engineering, Tsinghua University (GPA: 3.99/4.00).
- *2017.08 - 2021.07*, Undergraduate Student, Department of Electronic Engineering, Tsinghua University (GPA: 3.85/4.00).

# 💬 Invited Talks
- 2024.12 I gave a talk about MultifacetEval on the NLP Academic Exchange Platform. You can find replay [here](https://nice-nlp.github.io)

# 💻 Internships
- *2022.05 - Present*, iFlyTek, Beijing, China.
