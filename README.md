# Awesome Neural Symbolic
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)]()

A list of awesome neural symbolic papers.


## Contents
- [Contents](#contents)
- [Projects](#projects)
- [Papers](#papers)
  - [Survey](#survey)
  - [Proof Generation](#proof-generation)
  - [Automated Theorem Proving](#automated-theorem-proving)
  - [Programming](#programming)
  - [Symbolic Grounding](#symbolic-grounding)
  - [Visual Language Reasoning](#visual-language-reasoning)
- [Slides and Talks](#slides-and-talks)
- [Contribute](#contribute)


## Projects
- [Scallop](https://scallop-lang.github.io/)

## Papers

### Survey
- [Neurosymbolic Programming](https://www.cs.utexas.edu/~swarat/pubs/PGL-049-Plain.pdf) by Swarat Chaudhuri, Kevin Ellis, Oleksandr Polozov, Rishabh Singh,
Armando Solar-Lezama and Yisong Yue. Foundations and Trends® in Programming Languages 2021.
- [Neurosymbolic AI: The 3rd Wave](https://arxiv.org/pdf/2012.05876.pdf) by Artur d'Avila Garcez, Luis C. Lamb. 2020.

### Proof Generation
- [Code2Inv: A Deep Learning Framework for Program Verification](https://www.cs.mcgill.ca/~xsi/data/cav20.pdf) by Xujie Si, Aaditya Naik, Hanjun Dai, Mayur Naik, Le Song. CAV 2020.
- [Learning Loop Invariants for Program Verification](https://proceedings.neurips.cc/paper/2018/file/65b1e92c585fd4c2159d5f33b5030ff2-Paper.pdf) by Xujie Si, Hanjun Dai, Mukund Raghothaman, Mayur Naik, Le Song. NeurIPS 2018.

### Automated Theorem Proving
- [Manthan: A Data Driven Approach for Boolean Function Synthesis](https://arxiv.org/pdf/2005.06922.pdf) by Priyanka Golia, Subhajit Roy, Kuldeep S. Meel. CAV 2020.
- [Learning Symbolic Rules for Reasoning in Quasi-Natural Language](https://arxiv.org/abs/2111.12038) by Kaiyu Yang, Jia Deng.
- [Learning to Prove Theorems by Learning to Generate Theorems](https://arxiv.org/abs/2002.07019v2) by Mingzhe Wang, Jia Deng. NeurIPS 2020.
- [Learning to Reason in Large Theories without Imitation](https://arxiv.org/abs/1905.10501) by Kshitij Bansal, Christian Szegedy, Markus N. Rabe, Sarah M. Loos, Viktor Toman. 
- [DeepLogic: Towards End-to-End Differentiable Logical Reasoning](https://arxiv.org/abs/1805.07433) by Nuri Cingillioglu, Alessandra Russo. AAAI 2019.
  <details><summary>comments</summary>
  Check whether a logic program entails a given query. Does not rely on prior hand-coded structure.
  </details>
- [Guiding High-Performance SAT Solvers with Unsat-Core Predictions](https://arxiv.org/abs/1903.04671) by Daniel Selsam, Nikolaj Bjørner. SAT 2019.
- [Learning a SAT Solver from Single-Bit Supervision](https://arxiv.org/abs/1802.03685) by Daniel Selsam, Matthew Lamm, Benedikt Bünz, Percy Liang, Leonardo de Moura, David L. Dill. ICLR 2019.

### Programming
- [CURE: Code-Aware Neural Machine Translation for Automatic Program Repair](https://arxiv.org/abs/2103.00073) by Nan Jiang, Thibaud Lutellier, Lin Tan. ICSE 2021.
- [DreamCoder: Growing generalizable, interpretable knowledge with wake-sleep Bayesian program learning](https://arxiv.org/abs/2006.08381) by Kevin Ellis, Catherine Wong, Maxwell Nye, Mathias Sable-Meyer, Luc Cary, Lucas Morales, Luke Hewitt, Armando Solar-Lezama, Joshua B. Tenenbaum. 2020.
- [DeepProbLog: Neural Probabilistic Logic Programming](https://arxiv.org/abs/1805.10872) by Robin Manhaeve, Sebastijan Dumančić, Angelika Kimmig, Thomas Demeester, Luc De Raedt. NeurIPS 2018, Spotlight.
- [Learning to Infer Graphics Programs from Hand-Drawn Images](https://arxiv.org/abs/1707.09627) by Kevin Ellis, Daniel Ritchie, Armando Solar-Lezama, Joshua B. Tenenbaum. NeurIPS 2018, Spotlight.
- [Neuro-Symbolic Program Synthesis](https://arxiv.org/abs/1611.01855) by Emilio Parisotto, Abdel-rahman Mohamed, Rishabh Singh, Lihong Li, Dengyong Zhou, Pushmeet Kohli. ICLR 2017.

### Symbolic Grounding
- [Scallop: From Probabilistic Deductive Databases to Scalable Differentiable Reasoning](https://www.cis.upenn.edu/~mhnaik/papers/neurips21.pdf) by Jiani Huang, Ziyang Li, Binghong Chen, Karan Samel, Mayur Naik, Le Song, Xujie Si. NeurIPS 2021.
- [Techniques for Symbol Grounding with SATNet](https://www.cs.mcgill.ca/~xsi/data/neurips21a.pdf) by Sever Topan, David Rolnick, Xujie Si. NeurIPS 2021.
- [Temporal and Object Quantification Networks](http://toqnet.csail.mit.edu/data/papers/2021IJCAI-TOQNet.pdf) by Jiayuan Mao, Zhezheng Luo, Chuang Gan, Joshua B. Tenenbaum, Jiajun Wu, Leslie Pack Kaelbling, Tomer D. Ullman. IJACI 2021.
- [Logical Neural Networks](https://arxiv.org/abs/2006.13155) by Ryan Riegel, Alexander Gray, Francois Luus, Naweed Khan, Ndivhuwo Makondo, Ismail Yunus Akhalwaya, Haifeng Qian, Ronald Fagin, Francisco Barahona, Udit Sharma, Shajith Ikbal, Hima Karanam, Sumit Neelam, Ankita Likhyani, Santosh Srivastava. 2020.
- [SATNet: Bridging deep learning and logical reasoning using a differentiable satisfiability solver](https://arxiv.org/abs/1905.12149) by Po-Wei Wang, Priya L. Donti, Bryan Wilder, Zico Kolter. ICML 2019.
- [Neural Logic Machines](https://arxiv.org/pdf/1904.11694.pdf) by Honghua Dong, Jiayuan Mao, Tian Lin, Chong Wang, Lihong Li, Denny Zhou. ICLR 2019.

### Visual Language Reasoning
- [Composing Neural Learning and Symbolic Reasoning with an Application to Visual Discrimination](http://madhu.cs.illinois.edu/VDP_IJCAI2022.pdf) by Adithya Murali, Atharva Sehgal, Paul Krogmeier and P. Madhusudan. IJCAI 2022.
- [Grammar-Based Grounded Lexicon Learning](https://papers.nips.cc/paper/2021/hash/4158f6d19559955bae372bb00f6204e4-Abstract.html) by Jiayuan Mao, Freda Shi, Jiajun Wu, Roger Levy, Josh Tenenbaum. NeurIPS 2021.
- [Visually Grounded Neural Syntax Acquisition](https://arxiv.org/abs/1906.02890) by Haoyue Shi, Jiayuan Mao, Kevin Gimpel, Karen Livescu. ACL 2019 (Best Paper Nomination).
- [The Neuro-Symbolic Learner: Interpreting Scenes, Words, and Sentences From Natural Supervision](https://arxiv.org/abs/1904.12584) by Jiayuan Mao, Chuang Gan, Pushmeet Kohli, Joshua B. Tenenbaum, Jiajun Wu. ICLR 2019 (Oral).

## Slides and Talks
- [Data and Knowledge in Neuro-Symbolic Learning](http://starai.cs.ucla.edu/slides/Siemens22.pdf) by Guy Van den Broeck, 2022.
- [Neural (Meta) Program Synthesis](https://uclnlp.github.io/nampi/talk_slides/rishabh-singh-nampi-v2.pdf) by Google Brain, 2018.


## Contribute
We encourage all contributions to this repository. Open an [issue](https://github.com/Ying1123/awesome-neural-symbolic/issues) or send a [pull request](https://github.com/Ying1123/awesome-neural-symbolic/pulls).
