# Awesome Neural Symbolic
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)]()

A list of awesome neural symbolic papers.

## Contents
- [Contents](#contents)
- [Papers](#papers)
  - [Survey](#survey)
  - [Proof Generation](#proof-generation)
  - [Automated Theorem Proving](#automated-theorem-proving)
  - [Program Synthesis](#program-synthesis)
- [Slides and Talks](#slides-and-talks)
- [Contribute](#contribute)

## Papers

### Survey
- [Neurosymbolic Programming](https://www.cs.utexas.edu/~swarat/pubs/PGL-049-Plain.pdf) by Swarat Chaudhuri, Kevin Ellis, Oleksandr Polozov, Rishabh Singh,
Armando Solar-Lezama and Yisong Yue. Foundations and Trends® in Programming Languages 2021.

### Proof Generation
- [Code2Inv: A Deep Learning Framework for Program Verification](https://www.cs.mcgill.ca/~xsi/data/cav20.pdf) by Xujie Si, Aaditya Naik, Hanjun Dai, Mayur Naik, Le Song. CAV 2020.
  <details><summary>abstract</summary>
  Abstract. We propose a general end-to-end deep learning framework
  Code2Inv, which takes a verification task and a proof checker as input,
  and automatically learns a valid proof for the verification task by interacting with the given checker. Code2Inv is parameterized with an embedding   module and a grammar: the former encodes the verification task
  into numeric vectors while the latter describes the format of solutions
  Code2Inv should produce. We demonstrate the flexibility of Code2Inv by
  means of two small-scale yet expressive instances: a loop invariant synthesizer for C programs, and a Constrained Horn Clause (CHC) solver.
  </details>
  
  <details><summary>comments</summary>
  Empty.
  </details>
  
- [Learning Loop Invariants for Program Verification](https://proceedings.neurips.cc/paper/2018/file/65b1e92c585fd4c2159d5f33b5030ff2-Paper.pdf) by Xujie Si, Hanjun Dai, Mukund Raghothaman, Mayur Naik, Le Song. NeurIPS 2018.

### Automated Theorem Proving
- [Learning Symbolic Rules for Reasoning in Quasi-Natural Language](https://arxiv.org/abs/2111.12038) by Kaiyu Yang, Jia Deng.
- [Learning to Prove Theorems by Learning to Generate Theorems](https://arxiv.org/abs/2002.07019v2) by Mingzhe Wang, Jia Deng. NeurIPS 2020.
- [Learning to Reason in Large Theories without Imitation](https://arxiv.org/abs/1905.10501) by Kshitij Bansal, Christian Szegedy, Markus N. Rabe, Sarah M. Loos, Viktor Toman. 

### Program Synthesis
- [Neuro-Symbolic Program Synthesis](https://arxiv.org/abs/1611.01855) by Emilio Parisotto, Abdel-rahman Mohamed, Rishabh Singh, Lihong Li, Dengyong Zhou, Pushmeet Kohli. ICLR 2017.

## Slides and Talks
- [Neural (Meta) Program Synthesis](https://uclnlp.github.io/nampi/talk_slides/rishabh-singh-nampi-v2.pdf) by Google Brain, 2018

## Contribute
We encourage all contributions to this repository. Open an [issue](https://github.com/Ying1123/awesome-neural-symbolic/issues) or send a [pull request](https://github.com/Ying1123/awesome-neural-symbolic/pulls).