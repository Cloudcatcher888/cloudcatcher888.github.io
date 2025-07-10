---
permalink: /
title: "Zhikai Wang - SJTU"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Education
======
* Sept. 2019 – Sept. 2024, PhD @ [Data Driven Software Technology Lab](https://ddst.sjtu.edu.cn), [Department of Computer Science and Engineering](https://www.cs.sjtu.edu.cn/), [Shanghai Jiao Tong University, Shanghai, China 200240](https://www.sjtu.edu.cn/)  
  supervised by [Prof. Yanyan Shen](https://www.cs.sjtu.edu.cn/~shen-yy/). 

* Sept. 2015 – July 2019, Bachelor of Engineering at Shanghai Jiao Tong University. 

Work experience
======
* Oct. 2024 – Present: Algorithm Researcher & Joint Postdoctoral Researcher  
  * [Alibaba DAMO Academy, Foundation Intelligence Center](https://damo.alibaba.com/), focusing on research of multi-modal large models.  
  * Joint Postdoc at Fudan University.  
    - Postdoc Station Supervisor: **Prof. Deli Zhao**  
    - Mobile Station Supervisor: **Prof. Weihua Zhang**

* July 2023 – Sept. 2024: Research Intern  
  * Meituan, supervised by **Prof. Yichun Li**.

* Dec. 2021 – Dec. 2022: Research Intern  
  * Tencent, supervised by **Zibin Zhang** and **Kangyi Lin**.
  * We studied incremental learning for CTR prediction by resampling data with features which had not been updated for a while. We deployed our feature-staleness-aware CTR prediction method on the WeChat Official Accounts Platform and achieved prominent improvements in A/B test.

News
======
* 2023.03: Our paper “Incremental Learning for Multi-interest Sequential Recommendation” received the  
ICDE 2023 <font color="red">Best Paper Award (top 1)</font>!

Research interest
======
I'm interested in developing efficient models for recommendation systems (e.g., CTR prediction and sequential recommendation) and improving the generalization ability of models in incremental scenarios. Recently, I focus on multi-modal large models and their applications.

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
