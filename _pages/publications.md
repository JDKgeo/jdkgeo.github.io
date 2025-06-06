---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### Conference Papers

 * [CCS 2023] Pansilu Pitigalaarachchi, Xuhua Ding, Haiqing Qiu, **Haoxin Tu**, Jiaqi Hong, and Lingxiao Jiang, "**KRover: A Symbolic Execution Engine for Dynamic Kernel Analysis**", in *Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security (CCS 2023)*. [[PDF]](https://haoxintu.github.io/files/ccs2023_krover.pdf) [[Code]](https://github.com/KRoverSystems/KRover)
 * [ICSE 2023] **Haoxin Tu**, "**Boosting Symbolic Execution for Heap-based Vulnerability Detection and Exploit Generation**", in *the Doctoral Symposium Track of IEEE/ACM International Conference on Software Engineering (ICSE 2023)*. [[PDF]](https://haoxintu.github.io/files/icse23-ds-paper.pdf) [[Poster]](https://haoxintu.github.io/files/icse23-ds-poster.pdf)
 * [ESEC/FSE 2022] **Haoxin Tu**, Lingxiao Jiang, Xuhua Ding, and He Jiang, "**FastKLEE: Faster Symbolic Execution via Reducing Redundant Bound Checking of Type-Safe Pointers**", in *the Tool Demonstrations Track of ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2022)*. [[PDF]](https://haoxintu.github.io/files/fse2022-FastKLEE.pdf) [[Source Code]](https://github.com/haoxintu/FastKLEE) [[Video Demo]](https://youtu.be/iLLlZD384zM) [[Slides]](https://haoxintu.github.io/files/FastKLEE-slides.pdf)
 * [ISSRE 2022] **Haoxin Tu**, He Jiang, Xiaochen Li, Zhilei Ren, Zhide Zhou, and Lingxiao Jiang, "**RemGen: Remanufacturing A Random Program Generator for Compiler Testing**", in *the 33rd IEEE International Symposium on Software Reliability Engineering (ISSRE 2022)*. [[PDF]](https://haoxintu.github.io/files/issre2022-camera-ready.pdf) [[Code]](https://github.com/haoxintu/RemCCG) [[Slides]](https://haoxintu.github.io/files/RemGen-slides.pdf)


### Journals
 * [MPB 2023] **Jayaraj Dilipkumar**, and Palanisamy Shanmugam (2024), "**Fuzzy-based global water quality assessment and water quality cells identification using satellite data**", in *Marine Pollution Bulletin,*Volume 193, 2023, 115148, ISSN 0025-326X.[[Link]]([https://doi.org/10.1016/j.marpolbul.2023.115148].
 * [TSE 2024] **Haoxin Tu**, Lingxiao Jiang, Jiaqi Hong, Xuhua Ding, and He Jiang, "**Concretely Mapped Symbolic Memory Locations for Memory Error Detection**", in *IEEE Transactions on Software Engineering*, 2024. [[PDF]](https://haoxintu.github.io/files/SymLoc_TSE2024_Just_Accepted.pdf) [[Code]](https://github.com/haoxintu/SymLoc)
     * Also presented within *Journal first Paper Track* of the 39th IEEE/ACM International Conference on Automated Software Engineering (ASE 2024), Sacramento, California, United States.
 * [TR 2022] **Haoxin Tu**, He Jiang, Zhide Zhou, Yixuan Tang, Zhilei Ren, Lei Qiao, and Lingxiao Jiang, "**Detecting C++ Compiler Front-end Bugs via Grammar Mutation and Differential Testing**", in *IEEE Transactions on Reliability*, 2022. [[IEEE Early Access]](https://ieeexplore.ieee.org/document/9777893) [[Authors' Draft]](https://haoxintu.github.io/files/tr-2022-draft.pdf) [[Bug Reports]](https://github.com/haoxintu/CCOFT/blob/main/reported-bugs.md)

### Pre-prints
 * [Conference'25] **Haoxin Tu**, Lingxiao Jiang, and Marcel Böhme, "**Vital: Vulnerability-Oriented Symbolic Execution via Type-Unsafe Pointer-Guided Monte Carlo Tree Search**", *Under Review*, 2025. [[PDF]](https://arxiv.org/pdf/2408.08772)
 * [Conference'25] **Haoxin Tu**, Seongmin Lee, Yuxian Li, Peng Chen, Marcel Böhme, and  Lingxiao Jiang, "**Large Language Model-Driven Concolic Execution for Highly Structured Test Input Generation**." *Under Review*, 2025. [[PDF]](https://arxiv.org/pdf/2504.17542)


### Ph.D. Thesis

 * Dissertation submitted to [DUT](https://www.dlut.edu.cn/) (Defended on Dec 2023):
   * **Research on Test Program Construction Approaches for Compiler Testing and Debugging**
     * **(in Chinese: 面向编译器测试与调试的程序构造方法研究)** [[Thesis]](https://haoxintu.github.io/files/dut_thesis.pdf) [[Slides]](https://haoxintu.github.io/files/dut_phd_thesis_defense_slides.pdf)
 * Dissertation submitted to [SMU](https://www.smu.edu.sg/) (Defended on May 2025):
   * **Boosting Symbolic Execution for Vulnerablity Detection** [[Thesis]](https://haoxintu.github.io/files/smu_thesis.pdf) [[Slides]](https://haoxintu.github.io/files/smu_phd_thesis_defense_slides.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
