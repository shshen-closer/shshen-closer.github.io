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

* I am an associate researcher (postdoctor) at [the Institute of Artificial Intelligence, Hefei Comprehensive National Science Center](https://iai.ustc.edu.cn/iai/index.html). My collaborative supervisors are Prof. [Qi Liu](http://staff.ustc.edu.cn/~qiliuql/), and Prof. [Xun Chen](http://staff.ustc.edu.cn/~xunchen/).
* I received my Ph.D. degree in Data Science from the University of Science and Technology of China in July 2024, supervised by Prof. [Enhong Chen](http://staff.ustc.edu.cn/~cheneh/),  and received my Bachelor degree in Measurement and Control Technology and Instrument from Wuhan University in July 2018. 
* My research interests include data mining, knowledge discovery, user modeling, and intelligent education. <strong>If you have any questions regarding my research, or may be interested in potential collaboration, or would like to discuss any other matters, please do not hesitate to contact me. I look forward to the opportunity to cooperate with you.</strong>



<div class="content-grid" markdown="1">

<div class="main-column" markdown="1">

<h2 id="selected-publications">📝 Selected Publications</h2>
<p><em>( ✉ Corresponding Author, † Equal Contribution )</em></p>


<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href=""><strong>Towards Fine-grained Knowledge Tracing by Hierarchical Fusion of Multiple Question Attributes</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Qi Mo, Zhenya Huang, Yu Su, Linbo Zhu, Junyu, Qi Liu.</p>
    <p><em>ACM Transactions on Information Systems, 2026, accepted.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Knowledge tracing models typically treat each question as a single knowledge concept, ignoring the rich multi-attribute structure of real exam questions. This paper proposes a hierarchical fusion approach that jointly encodes multiple question attributes (e.g., concept tags, difficulty, type) at different granularities, enabling finer-grained modeling of student knowledge states and improving prediction accuracy on standard benchmarks.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href=""><strong>GLP-fusion: A Hierarchical Multimodal Fusion Framework for Robust Student Engagement Prediction</strong></a></p>
    <p>Zixuan Qin, <strong>Shuanghong Shen</strong>✉, Dengdi Sun, Keyu Zhu, Zhenya Huang, Qi Liu, Shijin Wang.</p>
    <p><em>IEEE Transactions on Multimedia, 2026, accepted.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Accurately predicting student engagement in online learning is challenging due to the heterogeneity of multimodal signals (video, audio, physiological). GLP-fusion introduces a hierarchical fusion framework that progressively integrates global context, local temporal dynamics, and personal behavioral patterns, achieving robust engagement prediction even under noisy or missing modality conditions.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/pii/S0306457325002924"><strong>LLM-EPSP: Large language model empowered early prediction of student performance</strong></a></p>
    <p>Huawei Zhou,  <strong>Shuanghong Shen</strong>✉, Yu Su, Yongchun Miao, Qi Liu, Linbo Zhu, Junyu Lu, Zhenya Huang.</p>
    <p><em>Information Processing & Management, 2026, 63(1): 104351.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Early prediction of student performance allows timely intervention, but existing methods struggle to leverage the rich semantic information in course materials and student interactions. LLM-EPSP harnesses large language models to extract deep semantic features from learning records, significantly improving early-stage prediction accuracy and providing interpretable risk signals for educators.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/pii/S089360802500677X"><strong>Practicing in quiz, assessing in quiz: A Quiz-based neural network approach for knowledge tracing</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Qi Liu, Zhenya Huang, Linbo Zhu, Junyu Lu, Kai Zhang.</p>
    <p><em>Neural Networks, 2025: 107797.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Traditional knowledge tracing models focus on individual question-answer interactions, overlooking the structured nature of quizzes as a learning unit. This paper proposes a quiz-centric neural network that models both intra-quiz dependencies and inter-quiz knowledge evolution, better reflecting how students actually practice and are assessed in real educational scenarios.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/pii/S0950705125004435"><strong>Harnessing code domain insights: Enhancing programming Knowledge Tracing with Large Language Models</strong></a></p>
    <p>Xinjie Sun, Qi Liu, Kai Zhang, <strong>Shuanghong Shen</strong>✉, Lina Yang, Hui Li.</p>
    <p><em>Knowledge-Based Systems, 2025, 317: 113396.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Programming knowledge tracing is uniquely challenging because code exercises carry rich structural and semantic information beyond simple right/wrong labels. This paper leverages LLMs to extract code domain insights—such as algorithmic concepts and error patterns—as auxiliary signals, substantially enhancing the accuracy of tracing students' programming skill acquisition.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ojs.aaai.org/index.php/AAAI/article/view/34611"><strong>ScholarGEC: Enhancing Controllability of Large Language Model for Chinese Academic Grammatical Error Correction</strong></a></p>
    <p>Zixiao Kong, Xianquan Wang, <strong>Shuanghong Shen</strong>✉, Keyu Zhu, Huibo Xu, Yu Su.</p>
    <p><em>Proceedings of the AAAI Conference on Artificial Intelligence. 2025, 39(23): 24339-24347.</em> [C]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Chinese academic writing contains domain-specific grammatical patterns that general GEC systems fail to handle well. ScholarGEC introduces a controllable LLM-based framework that incorporates academic style constraints and error-type guidance, enabling more precise and context-aware grammatical error correction tailored to scholarly Chinese text.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709275"><strong>Mitigating Redundancy in Deep Recommender Systems: A Field Importance Distribution Perspective</strong></a></p>
    <p>Xianquan Wang, Likang Wu, Zhi Li, Haitao Yuan, <strong>Shuanghong Shen</strong>✉, Huibo Xu, Yu Su, Chenyi Lei.</p>
    <p><em>Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 1. 2025: 1515-1526.</em> [C]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Deep recommender systems often suffer from feature redundancy across input fields, leading to wasted model capacity and degraded performance. This paper analyzes the problem from a field importance distribution perspective and proposes a principled method to identify and suppress redundant fields, yielding more efficient and accurate recommendations on large-scale industrial datasets.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ieeexplore.ieee.org/abstract/document/10494775"><strong>A Survey of Knowledge Tracing: Models, Variants, and Applications</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Qi Liu, Zhenya Huang, Yonghe Zheng, Minghao Yin, Minjuan Wang, Enhong Chen.</p>
    <p><em>IEEE Transactions on Learning Technologies, 2024, 17: 1858-1879.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">This comprehensive survey systematically reviews over 100 knowledge tracing models, organizing them into a unified taxonomy covering deep learning-based, cognitive theory-inspired, and graph-based variants. It also summarizes key datasets, evaluation protocols, and open challenges, serving as a thorough reference for researchers entering the intelligent education field.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417424011254"><strong>Constructing a Confidence-guided Multigraph Model for cognitive diagnosis in personalized learning</strong></a></p>
    <p>Yu Su, Ze Han, <strong>Shuanghong Shen</strong>✉, Xuejie Yang, Zhenya Huang, Jinze Wu, Huawei Zhou, Qi Liu.</p>
    <p><em>Expert Systems with Applications, 2024, 252: 124259.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Cognitive diagnosis aims to infer students' mastery of fine-grained knowledge concepts, but existing models often ignore the uncertainty in student responses. This paper constructs a confidence-guided multigraph model that explicitly captures response confidence alongside concept relationships, leading to more reliable and interpretable cognitive diagnosis for personalized learning.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423021395"><strong>Global and Local Neural Cognitive Modeling for Student Performance Prediction</strong></a></p>
    <p>Yu Su, <strong>Shuanghong Shen</strong>✉, Enhong Chen, Qi Liu, Zhenya Huang, Wei Huang, Yu Yin, Yu Su, Shijin Wang.</p>
    <p><em>Expert Systems with Applications, 2024, 237: 121637.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Student performance prediction requires capturing both long-range learning trends and short-term behavioral fluctuations. This paper proposes a dual-branch neural cognitive model that jointly learns global learning trajectories and local interaction patterns, outperforming single-scale baselines and providing richer representations for downstream educational applications.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ieeexplore.ieee.org/abstract/document/9950313"><strong>Monitoring Student Progress for Learning Process-Consistent Knowledge Tracing</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Enhong Chen, Qi Liu, Zhenya Huang, Wei Huang, Yu Yin, Yu Su, Shijin Wang.</p>
    <p><em>IEEE Transactions on Knowledge and Data Engineering, 2023, 35(8): 8213-8227.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Existing knowledge tracing models often fail to maintain consistency between a student's observed learning behaviors and their predicted knowledge state. This paper introduces a progress monitoring mechanism that tracks learning dynamics over time and enforces process-consistent constraints, resulting in more coherent and accurate knowledge state estimation published in IEEE TKDE.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://dl.acm.org/doi/abs/10.1145/3477495.3531939"><strong>Assessing Student’s Dynamic Knowledge State by Exploring the Question Difficulty Effect</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Zhenya Huang, Qi Liu, Yu Su, Shijin Wang, Enhong Chen.</p>
    <p><em>Proceedings of the 45th international ACM SIGIR conference on research and development in information retrieval. 2022: 427-437.</em> [C]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Question difficulty is a critical but often overlooked factor in knowledge tracing. This SIGIR paper proposes a difficulty-aware model that explicitly disentangles the effect of question difficulty from student ability, enabling more accurate and interpretable assessment of students' dynamic knowledge states across varying difficulty levels.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://dl.acm.org/doi/abs/10.1145/3447548.3467237"><strong>Learning Process-consistent Knowledge Tracing</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Qi Liu, Enhong Chen, Zhenya Huang, Wei Huang, Yu Yin, Yu Su, Shijin Wang.</p>
    <p><em>Proceedings of the 27th ACM SIGKDD conference on knowledge discovery & data mining. 2021: 1452-1460.</em> [C]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Standard knowledge tracing models treat student responses as independent events, ignoring the inherent consistency constraints of a real learning process (e.g., a student who masters a concept should not regress without cause). This KDD paper formalizes learning process consistency as an explicit training objective, significantly improving both predictive performance and the interpretability of traced knowledge states.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://dl.acm.org/doi/abs/10.1145/3397271.3401288"><strong>Convolutional Knowledge Tracing: Modeling Individualization in Student Learning Process</strong></a></p>
    <p><strong>Shuanghong Shen</strong>, Qi Liu, Enhong Chen, Han Wu, Zhenya Huang, Weihao Zhao, Yu Su, Haiping Ma, Shijin Wang.</p>
    <p><em>Proceedings of the 43rd international ACM SIGIR conference on research and development in information retrieval. 2020: 1857-1860.</em> [C]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Different students exhibit distinct learning patterns even when studying the same material. This SIGIR paper proposes a convolutional knowledge tracing model that uses local convolutional filters to capture individualized learning behaviors within sequential interaction data, offering a lightweight yet effective alternative to recurrent architectures.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=600&auto=format&fit=crop" alt="Paper Overview">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/pii/S0957417425018378"><strong>Live Streaming Recommendation Based on Multiple Types of Repeated Behaviors</strong></a></p>
    <p>Mengxiao Zhu, Qi Shu, <strong>Shuanghong Shen</strong>, Li Feng, Jiancan Wu, Zhenya Huang.</p>
    <p><em>Expert Systems with Applications, 2025: 128217.</em> [J]</p>
    <p class="paper-intro" style="font-size: 0.9em; color: #555; margin-top: 0.5rem;">Repeated behaviors (re-watching, re-entering a live room) are strong but heterogeneous signals in live streaming platforms. This paper categorizes and models multiple types of repeated behaviors within a unified recommendation framework, capturing users' evolving interests more accurately and improving recommendation quality on real-world live streaming data.</p>
  </div>
</div>



# 🎖 Honors and Awards {#honors-and-awards}
- *2023*: The Special Prize of President Scholarship of Postgraduate Students. 
- *2023*: China National Scholarship.
- *2023*: Best Applied Paper of CCF BigData2023.
- *2023*: Top 1 in the [AAAI'2023 Global Knowledge Tracing Challenge](https://ai4ed.cc/competitions/aaai2023competition).
- *2023*: Top 4 in Task 2 of the [Baidu 2023 CTI Challenge](https://aistudio.baidu.com/aistudio/projectdetail/6120125).
- *2022*: Top 1 in Task 4 of the [NeurIPS'2022 CausalML Challenge](https://eedi.com/projects/neurips-2022). 
- *2022*: Top 1 in Track 1 and Track 2 of the first phase, and Top 1 in Track 1, Top 2 in Track 2 of the second phase, of the [EDM'2022 2nd CSEDM Data Challenge](https://eedi.com/projects/neurips-2022).
- *2021*: Top 10 in Task 1 of the [Tecent 2021 Advertising Algorithm Challenge](https://algo.qq.com/).
- *2020*: Top 1 in Task 2 of the [NeurIPS 2020 Education Challenge](https://eedi.com/projects/neurips-education-challenge).


# 📖 Educations {#educations}
- *2018.09 - 2024.06*, School of Artificial Intelligence and Data Science, University of Science and Technology of China. 
- *2014.09 - 2018.06*, School of Electronic Information, Wuhan University. 

# 💬 Services {#services}
- *Journal Reviewer*

    * IEEE Transactions on Knowledge and Data Engineering
    * IEEE Transactions on Neural Networks and Learning Systems
    * IEEE Transactions on Systems, Man, and Cybernetics publication information
    * IEEE Transactions on Learning Technologies
    * IEEE Transactions on Emerging Topics in Computational Intelligence
    * ACM Transactions on Information Systems
    * Expert Systems with Applications
    * Knowledge-Based Systems
    * Information Processing and Management

- *Program Committee Member*

    * SIGIR
    * AAAI
    * KDD
    * IJCAI
    * TheWebConf

# 💻 Internships {#internships}
- *2018.03 - 2018.08*, [IflyTek](https://www.iflytek.com/en/), Hefei, China.
- *2017.07 - 2017.09*, [Tsmc](https://www.tsmc.com/schinese), Shanghai, China.
</div>

<div class="side-column" markdown="1">

<div class="news-box" markdown="1">

# 🔥 News {#news}

- *2026.01*: 🎉🎉 One paper accepted by ACM Transactions on Information Systems.
- *2025.12*: 🎉🎉 One paper accepted by IEEE Transactions on Multimedia.
- *2025.08*: 🎉🎉 One paper accepted by Information Processing & Management.
- *2025.07*: 🎉🎉 One paper accepted by Neural Networks.
- *2025.04*: 🎉🎉 One paper accepted by Knowledge-Based Systems.
- *2024.12*: 🎉🎉 One paper accepted by AAAI 2025.
- *2024.11*: 🎉🎉 One paper accepted by KDD 2025.

</div>

</div>

</div>
