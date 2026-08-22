---
title: "ICAPS'26 Workshop: PR-BGI"
date: 2025-04-13T00:00:00+00:00
draft: false
---

# Workshop on Planning and Reasoning about Beliefs, Goals and Intentions (PR-BGI)

ICAPS 2026 Workshop <br/>
Dublin, Ireland
June 28, 2026


## Program

<style>
.program-table table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 3rem;
}
.program-table th,
.program-table td {
  padding: 10px 14px;
  border: 1px solid #e0e0e0;
  text-align: left;
  vertical-align: top;
  line-height: 1.5;
}
.program-table thead th {
  background: #f5f5f5;
  font-weight: 700;
}
.program-table td:first-child,
.program-table th:first-child {
  white-space: nowrap;
  width: 1%;
}
.program-table tbody tr:nth-child(even) {
  background: #fafafa;
}
</style>

<div class="program-table">

| Time        | Session                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 14:30–14:34 | Opening remarks                                                                                                                                                                               |
| 14:34–15:24 | [**Invited talk: Implicitly Coordinating Agents**](#invited-talk)<br>[Thomas Bolander](http://www2.compute.dtu.dk/~tobo/)                                                                       |
| 15:24–15:36 | [**SMT-Based Goal and Plan Recognition**](https://drive.google.com/file/d/1EwjY2q9Cddit5OzjiMbcaRFg5XWJf7ko/view?usp=sharing)<br>Kin Max Piamolini Gusmão, Joan Espasa, Miquel Ramirez, Mustafa Faisal Zaki Abdelwahed, Nir Lipovetzky, Felipe Meneguzzi                            |
| 15:36–15:48 | [**Divergence Identities for Probabilistic Goal Recognition**](https://drive.google.com/file/d/12hFlnb_1WqZrk486nYSCKoEh3GA0V1bH/view?usp=sharing)<br>Giacomo Rosa, Nir Lipovetzky, Jean Honorio, Sebastian Sardina                                                                 |
| 15:48–16:00 | [**Generation of Suspicious Behaviour**](https://drive.google.com/file/d/1bq_BxiRbCTsS37WFVFStwKLTy6Zio1Ox/view?usp=sharing)<br>Peta Masters, Daniel Gallagher, Gal A Kaminka, Mor Vered                                                                                            |
| 16:00–16:20 | Official tea break                                                                                                                                                                            |
| 16:20–16:35 | IPC competition session                                                                                                                                                                       |
| 16:35–16:47 | [**Concurrent Action Models for DEL**](https://drive.google.com/file/d/1mgUQ_Ys9zanNE1-3j_PbdYMPP_-FSGaS/view?usp=sharing)<br>Ludovico Deponte                                                                                                                                      |
| 16:47–16:59 | [**RP-M*P: Towards Extending Epistemic Planning with Custom Modalities**](https://drive.google.com/file/d/1YwQ0FMXS_UIS68bRv4cVoh1qTKppGYPJ/view?usp=sharing)<br>Rebecca Leah De Venezia, Christian Muise                                                                      |
| 16:59–17:11 | [**A LETHEIA: Adaptive Epistemic Planning over Kripke Models with DEL Product-Update Semantics**](https://drive.google.com/file/d/1xfxybKKMNYq8urcnuMRsz_3m2pF3i8Jl/view?usp=sharing)<br>Haniel Ulises Vasquez Morales                                                              |
| 17:11–17:23 | [**Epistemic Ambiguity Is a Design Problem: Toward Complete Online Planning with Verified Actions**](https://drive.google.com/file/d/1EJgqpLeLUAbWOHQ_yn2ANgsa6CXSbBtn/view?usp=sharing)<br>Halim Djerroud                                                                          |
| 17:23–17:35 | [**Synthesis Under Multi-Agent Environment Assumptions for Specifications in Linear Temporal Logic on Finite Traces**](https://drive.google.com/file/d/1KGsk2QSIAyi8lF3gDbNBXZ6KIbwQfjUS/view?usp=sharing)<br>Stella Condrò, Giuseppe De Giacomo, Gianmarco Parretti, Elisa Santini |
| 17:35–17:47 | [**Synthesis Foundations for Online LTLf Goal Management**](https://drive.google.com/file/d/1V6X8S7Non6vo7oFNCVytHZPIXJgizM2H/view?usp=sharing)<br>Giuseppe De Giacomo, Yves Lesperance, Gianmarco Parretti, Fabio Patrizi                                                          |
| 17:47–17:59 | [**Hardness of MAPF under Destination Uncertainty**](https://drive.google.com/file/d/1oMkWj-gKYlhflXeMXBDmeBLfPSpQ8sS-/view?usp=sharing)<br>P. Maurice Dekker                                                                                                                       |
| 17:59–18:00 | Closing remarks                                                                                                                                                                               |

</div>



## Invited Talk

**Title:** Implicitly Coordinating Agents

**Speaker:** [Thomas Bolander](http://www2.compute.dtu.dk/~tobo/), Technical University of Denmark (DTU)

**Bio:** Thomas Bolander is a Professor in logic and artificial intelligence at DTU Compute, the Department of Applied Mathematics and Computer Science at the Technical University of Denmark. His research centers on logic and AI, with particular interests in social intelligence, multi-agent systems, modal and epistemic logic, and automated planning. He is a leading contributor to epistemic planning based on dynamic epistemic logic (DEL) and its applications to multi-agent reasoning and human–robot collaboration.

**Abstract:** To achieve multi-agent coordination without explicit communication, it is essential for agents to be able to reason about the beliefs, knowledge, capabilities, intentions, and attention of other agents. A framework well suited for an AI agent to model such aspects of the mental states of other agents is Dynamic Epistemic Logic (DEL). In automated planning based on DEL (epistemic planning), one can define a notion of implicit coordination where agents coordinate their actions exclusively through observing the actions of others. If I see you lift one side of a heavy box, I know you expect me to lift the other. In order for implicit coordination to also be used for plan and goal recognition, one needs to import ideas from the concept of forward induction in game theory.

In my talk, I will briefly introduce epistemic planning based on DEL, then introduce implicit coordination and forward induction, and illustrate the use of these ideas and techniques for human-robot collaboration.



## Aim and Scope of the Workshop
We invite submissions to the workshop on Planning and Reasoning about Beliefs, Goals, and Intentions (PR-BGI). This workshop focuses on enabling autonomous agents to effectively operate in shared environments alongside other agents and human.
Modern autonomous systems, such as robots, delivery vehicles, and drones, must reason about the behaviour and expectations of others. In many scenarios, explicit communication is limited or unavailable, making it essential for agents to reason about others’ beliefs, goals, and intentions in order to coordinate and interact effectively.
Research areas such as epistemic planning, goal recognition, intention recognition, and theory of mind provide principled approaches to this problem. However, these methods are often developed in isolation and face challenges in scalability, integration, and real-world deployment.
This workshop aims to bring together researchers and practitioners to bridge the gap between methods for reasoning about other agents’ beliefs, goals, and intentions and the practical requirements of autonomous systems operating in shared environments. The focus is on understanding how planning-based and inference-based approaches can support interaction and coordination in realistic scenarios, and how real-world constraints, such as decentralization, limited communication, and human involvement, should inform future theoretical work.



## Topics of Interest
Topics include, but are not limited to:
- Epistemic planning
- Reasoning about individual, group, and distributed beliefs
- Goal recognition and intention recognition
- Planning in multi-agent and human–agent settings
- Decentralized and interaction-aware planning
- Trade-offs between expressiveness, scalability, and deployability
- Empirical evaluation, benchmarks, and real-world case studies

We particularly encourage submissions that highlight practical challenges, design trade-offs, and lessons learned from real-world applications.




## Submission Instructions
We invite the following types of submissions:
- Full technical papers (up to 9 pages, excluding references)
- Short technical papers (up to 5 pages, excluding references)
- Position papers discussing open challenges, new perspectives, negative results, or practical experiences (up to 5 pages, excluding references)

All submissions will be peer-reviewed based on relevance, quality, and their potential to stimulate discussion. We plan for accepted papers to be included in the archival workshop proceedings. At least one author of each accepted paper is expected to attend the workshop and present the work.


Submissions will be hosted on [ChairingTool](https://chairingtool.com/conferences/icaps-prbgi-26/main-track/)
Please ensure that you have registered with ChairingTool. 
<!-- New profiles with an institutional email will be activated immediately. However, new profiles without an institutional email may take up to two weeks to be activated. -->

Papers must be prepared according to the instructions for ICAPS 2026 (in AAAI format) available at: [Paper template](https://aaai.org/authorkit26-1/).



## Important Dates

* **Paper submission deadline: ~~May 18~~ May 25, 2026 UTC-12**
* Notification of acceptance: June 10, 2026 UTC-12
* Camera-ready paper submissions: June 24, 2026 UTC-12

* **Workshop date: June 28 afternoon**, 2026



## Accepted Papers

- **[RP-M*P: Towards Extending Epistemic Planning with Custom Modalities](https://drive.google.com/file/d/1YwQ0FMXS_UIS68bRv4cVoh1qTKppGYPJ/view?usp=sharing)**  
  Rebecca Leah De Venezia, Christian Muise

- **[Hardness of MAPF under Destination Uncertainty](https://drive.google.com/file/d/1oMkWj-gKYlhflXeMXBDmeBLfPSpQ8sS-/view?usp=sharing)**  
  P. Maurice Dekker

- **[SMT-Based Goal and Plan Recognition](https://drive.google.com/file/d/1EwjY2q9Cddit5OzjiMbcaRFg5XWJf7ko/view?usp=sharing)**  
  Kin Max Piamolini Gusmão, Joan Espasa, Miquel Ramirez, Mustafa Faisal Zaki Abdelwahed, Nir Lipovetzky, Felipe Meneguzzi

- **[Divergence Identities for Probabilistic Goal Recognition](https://drive.google.com/file/d/12hFlnb_1WqZrk486nYSCKoEh3GA0V1bH/view?usp=sharing)**  
  Giacomo Rosa, Nir Lipovetzky, Jean Honorio, Sebastian Sardina

- **[Epistemic Ambiguity Is a Design Problem: Toward Complete Online Planning with Verified Actions](https://drive.google.com/file/d/1EJgqpLeLUAbWOHQ_yn2ANgsa6CXSbBtn/view?usp=sharing)**  
  Halim Djerroud

- **[Synthesis Under Multi-Agent Environment Assumptions for Specifications in Linear Temporal Logic on Finite Traces](https://drive.google.com/file/d/1KGsk2QSIAyi8lF3gDbNBXZ6KIbwQfjUS/view?usp=sharing)**  
  Stella Condrò, Giuseppe De Giacomo, Gianmarco Parretti, Elisa Santini

- **[Synthesis Foundations for Online LTLf Goal Management](https://drive.google.com/file/d/1V6X8S7Non6vo7oFNCVytHZPIXJgizM2H/view?usp=sharing)**  
  Giuseppe De Giacomo, Yves Lesperance, Gianmarco Parretti, Fabio Patrizi

- **[A LETHEIA: Adaptive Epistemic Planning over Kripke Models with DEL Product-Update Semantics](https://drive.google.com/file/d/1xfxybKKMNYq8urcnuMRsz_3m2pF3i8Jl/view?usp=sharing)**  
  Haniel Ulises Vasquez Morales

- **[Concurrent Action Models for DEL](https://drive.google.com/file/d/1mgUQ_Ys9zanNE1-3j_PbdYMPP_-FSGaS/view?usp=sharing)**  
  Ludovico Deponte

- **[Generation of Suspicious Behaviour](https://drive.google.com/file/d/1bq_BxiRbCTsS37WFVFStwKLTy6Zio1Ox/view?usp=sharing)**  
  Peta Masters, Daniel Gallagher, Gal A Kaminka, Mor Vered



## Organizing Committee

- **[Dr. Chenyuan Zhang](https://chen-yuan-zhang.github.io/)**  
  Monash University, Australia

- **[Dr. Guang Hu](https://guanghuhappysf128.github.io/)**  
  University of Melbourne, Australia

- **[Dr. Alessandro Burigana](https://a-burigana.github.io)**  
  Free University of Bozen-Bolzano, Italy 


- **[Dr. Francesco Fabiano](https://francescofabiano.github.io/)**  
  University of Oxford, UK

- **[Prof. Tim Miller](https://uqtmiller.github.io/)**  
  The University of Queensland, Australia
  