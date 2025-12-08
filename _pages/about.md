---
permalink: /
title: "Brief Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an Assistant Professor in the [Department of Computer Science](https://cis.cornell.edu/) at Cornell University.
I received my PhD in Computer Science from UC Berkeley. I work in the field of high-performance computing (HPC) for large-scale computational sciences and lead the Cornell HPC group. I'm interested in developing algorithms and software infrastructures on parallel machines to speed up data processing without sacrificing programming productivity, and to make high-performance computing more accessible. I'm a big fan of sparse linear algebra and believe in sparse linear algebra as a computational abstraction for tackling large-scale computational challenges.

<!-- 
A data-driven personal website
====== -->

I received the [2024 SIAG/Supercomputing Early Career Prize](https://www.siam.org/prizes-recognition/activity-group-prizes/detail/siag-sc-early-career-prize), the [2023 ISSNAF Young Investigator Mario Gerla Award](https://cis.cornell.edu/guidi-wins-issnaf-young-investigator-mario-gerla-award), and the [2020 SIGHPC Computational & Data Science Fellowship](https://www.sighpc.org/for-your-career/fellowships/2020-fellowship-winners?fbclid=IwAR2N8swtCYgNH3phRmrFtASSC42b4oN5joG1l5XHFSdnkMY6U4HvZt3olLE). 

I'm an Affiliate Faculty in the Applied Math and Computational Sciences Division (Performance and Algorithms Group) at Lawrence Berkeley National Laboratory and a Graduate Field Faculty in the [School of Electrical and Computer Engineering](https://www.engineering.cornell.edu/ece/), [Department of Computational Biology](https://gradschool.cornell.edu/academics/fields-of-study/field/computational-biology/) and the [Center for Applied Math](https://www.cam.cornell.edu/cam) at Cornell.

I'm also a faculty member of the [Computer Systems Laboratory (CSL) at Cornell University](https://www.csl.cornell.edu/).

I’ll be **recruiting PhD students for Fall 2026 to join my group** at [Cornell CS](https://cis.cornell.edu/). Our research spans parallel computation, sparse linear algebra, programming systems, large-scale computational biology challenges, and algorithms for emerging hardware architectures.
Projects focus on parallel scientific computation, including—but not limited to—real-world large-scale challenges in computational biology and emerging hardware technologies. Prior biology knowledge is not required, but a background in parallel computing and C/C++ programming is highly encouraged.

The group fosters a collegial, collaborative culture in the beautiful natural surroundings of Ithaca, NY. You'll likely enjoy Ithaca much more than you expect!

Due to limited time, I’m mostly unable to respond to individual email inquiries. If you’re interested, **please apply to the Cornell CS PhD program and mention my name in your application materials**, along with why you’re interested in working with me. The applications are submitted through the [department](https://www.cs.cornell.edu/phd-computer-science/apply).

<!--and the Tl;dr version of my **[Research Statement](https://drive.google.com/file/d/1_HVC4HkkyBMqUx8AiTHeyjgwlSdYG3j6/view?usp=sharing)**.-->

Publications, Talks, Teaching
------
For a complete list of publications, talks, and teaching information, please see my **[CV](https://drive.google.com/file/d/1l2TewcjYoSb-27kNmy54glEZa6Wvc6mR/view?usp=sharing)** (I'm fairly good at keeping it up to date) or my [Google Scholar](https://scholar.google.com/citations?user=UZLC4TYAAAAJ) account. The PDFs of most of my articles can be found on arXiv. 

If you're interested in course or research talk slides, please feel free to email me. I'll add them here eventually.

Recent Updates
------

**4/24/2025** 
I'm very pleased to announce that our [NSF](https://www.nsf.gov/) proposal "ACED: Fast and Scalable Whole Genome Analysis on Emerging Hardware Technologies" was awarded. This project, conducted in collaboration with [Professor April Wei's Lab](https://aprilweilab.github.io/), will address major computational challenges in population genetics through parallel computation, sparse linear algebra, and new hardware technologies.

Selected Publication & GitHub
------

**Popcorn: Accelerating Kernel K-means on GPU**  
Our PPoPP 2025 paper introduces a new sparse-matrix formulation of Kernel K-means that enables an efficient, high-performance GPU implementation. Our open-source tool, **Popcorn**, achieves up to **123.8× speedup over a CPU version** and **2.6× over a dense GPU implementation**.

[Read the Popcorn Paper](https://arxiv.org/pdf/2501.05587)

[Popcorn GitHub](https://github.com/HicrestLaboratory/Matrix-Centric-K-Means)

**HySortK: High-Performance Sorting-Based K-mer Counting in Distributed Memory with Flexible Hybrid Parallelism**  
Our ICPP 2024 paper describes **HySortK**, a new distributed-memory k-mer counting tool for genomics pipelines. Using a sorting-based approach and a flexible hybrid-parallelism layer, HySortK significantly reduces memory overhead and improves scalability, achieving **2–10× speedup over a GPU baseline on 4–8 nodes** and up to **2× speedup over leading CPU tools on 16 nodes**, while reducing peak memory usage by approximately 30%. 

[Read the HySortK Paper](https://arxiv.org/abs/2407.07718)

[HySortK GitHub](https://github.com/CornellHPC/HySortK)

<!-- Cornell HPC Group
------

I'm the proud PhD (co-)advisor of:

* [Julian Bellavita](https://jb2695.wixsite.com/jbellavita) (2023 --)
* [Ben Landrum](http://ben-landrum.com/) with [Professor Alex Conway](https://ajhconway.com/) (2024 --)
* [Irene Simó Muñoz](https://isimo00.github.io/) (2025 --)

Current MEng students:

* Andrew Chang
* Nakul Iyer
* Matthew Rubino

Current undergraduate students:

* Noam Benson-Tilsen (PhD student at Yale starting Fall 2025)
* Thomas McFarland
* Aaron Li
* Nolan Lizmi
* Zander Scharzberg

For a complete list of current and past students, please see my **[CV](https://drive.google.com/file/d/1DmJgPIFg6S-B0bqvqWFUmrmk6czYVmy5/view?usp=sharing)**. I'll likely hire one PhD student with background in parallel programming and interest in high-performance computing for computational sciences next year (to start Fall 2026). The admissions process is through [Cornell CIS](https://www.cs.cornell.edu/phd/admissions) and not through me personally.

Useful Resources for Students
------

The list is under construction but in the meantime:

* [A doc with advice related to graduate school application](https://docs.google.com/document/d/1et1FK4_GlAZrxd7JoPzfqcLAZh_9sOm7HMov_hDGo98/preview?pli=1) (I wrote this as a graduate student at UCB, but it generally applies to any research university).
* [A repository with advice related to graduate school application, research, and PhD related to (mostly) CS, NLP, and ML](https://github.com/shaily99/advice).
* [A curated list of application resources for prospective graduate students in Computer Science](https://github.com/chinasaokolo/csGraduateApps).
* [Non-Technical Talks by David Patterson, UC Berkeley](https://people.eecs.berkeley.edu/~pattrsn/talks/nontech.html).
* [How to Give a Good Colloquium by John E. McCarthy, Washington University in St. Louis](https://drive.google.com/file/d/1AQJXRWYYY4o6AnBGB26NXccOdgnbMdQw/view?usp=sharing).
 -->
