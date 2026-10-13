---
title: "ICAPS'26 Workshop: GenPlan"
date: 2025-04-21T00:00:00+00:00
draft: false
---

# Workshop on Generalization in Planning (GenPlan)

ICAPS 2026 Workshop<br>
Dublin, Ireland, June 28, 2026<br>

Official Website: [https://aair-lab.github.io/genplan26](https://aair-lab.github.io/genplan26)

## Aim and Scope of the Workshop

Generalization and transfer are essential components of intelligence, and significant research efforts have been dedicated to addressing these challenges in sequential decision-making. However, this research is often fragmented across largely parallel research communities such as AI planning, reinforcement learning, model learning, robotics, etc. Recent advances in deep reinforcement learning and generative AI have led to data-driven methods that are effective for short-horizon reasoning and decision-making, with open problems regarding sample efficiency, guarantees of correctness, and applicability to long-horizon settings. Conversely, the AI planning community has made complementary strides, developing robust analytical methods that enable sample-efficient generalization and transferability in long-horizon planning, with open problems in designing and modeling the necessary representations.

Humans are good at solving sequential decision-making problems, generalizing from a few examples, and learning skills that can be transferred to solve unseen problems. However, these problems remain long-standing open problems in AI. This workshop will feature a synthesis of the best ideas on the topic from multiple highly active research communities. We welcome submissions addressing the problem of generalizable and transferable learning in all forms of sequential decision-making. This event represents the eighth edition of the recurring and well-attended GenPlan series of Workshops.

## Topics of Interest

The workshop will focus on research related to all aspects of learning, generalization, and transfer in sequential decision-making (SDM). This topic features technical problems that are of interest not only in multiple subfields of AI research (including reinforcement learning, automated planning, and learning for knowledge representation) but also in other fields of research, including formal methods and program synthesis. We will welcome submissions that address formal as well as empirical issues on topics such as:
- Formulations of generalized SDM problems.
- Learning for transfer and generalization in reinforcement learning.
- Learning and representing hierarchical policies and behaviors for SDM.
- Learning and synthesis of generalizable solutions for SDM problem classes.
- Learning paradigms, representations, and algorithms for transferring learned knowledge and solutions to new SDM problems.
- Learning and representing generalized Q/V-functions and heuristics for plan and policy generalization.
- Learning high-level models and hierarchical solutions for generalizable SDM.
- Neuro-symbolic approaches for generalization and transfer in SDM.
- Few-shot learning and transfer for SDM.
- Meta-learning for generalizable policies.
- Learning for program synthesis.
- Learning domain control knowledge and partial policies.
- Representation of solution structures that enable generalization and transfer.

## Keynote Speakers

- [David Abel](https://david-abel.github.io/), Google DeepMind & University of Edinburgh
- [Anders Jonsson](https://www.upf.edu/web/anders-jonsson), Universitat Pompeu Fabra
- [Tom Silver](https://tomsilver.github.io/), Princeton University

## Submission Instructions

Submissions can describe either work in progress or mature work that would be of interest to researchers working on generalization in planning. We also welcome “highlights” papers summarizing and highlighting results from multiple recent papers by the authors. Preference will be given to new work (including highlights) and work in progress rather than exact resubmissions of previously published work.

Submissions of papers being reviewed at other venues are welcome since GenPlan is a non-archival venue, and we will not require a transfer of copyright.

GenPlan requires all submissions to be anonymized.

Two types of papers can be submitted:
- full technical papers with the length of up to 8 pages + references
- short papers with the length between 3 and 5 pages + references

Submissions may use as many pages of appendices (after the references) as they wish, but the reviewers are not required to read the appendix. Submissions should use the ICAPS paper format. We also welcome submission in the the NeurIPS format. However, we will require camera-ready version of the paper in the ICAPS format.

Now accepting submissions through OpenReview: [https://bit.ly/SubmitToGenPlan26](https://bit.ly/SubmitToGenPlan26).

## Important Dates
- Paper Submission Deadline: ~~May 1, 2026~~ May 15, 2026 (11:59 PM AoE)
- Author Notification: June 8, 2026
- Camera-ready Version Due: July 15, 2026
- Workshop: June 28, 2026

## Schedule

<div class="program-table">

| Time        | Session |
| ----------- | ------- |
| | **Session 1 — Learning Planning Models from Demonstration & Perception** |
| 9:00–9:30   | **Keynote: Tom Silver** |
| 9:30–9:50   | [Learning Lifted Symbolic Planning Domains from Image Sequences (VISA)](https://openreview.net/pdf?id=sbWpO5k1gA)<br>*Ulzhalgas Rakhman, Paul Schulte, Hector Geffner* |
| 9:50–10:10  | Learning HTNs from Visual Demonstration with VLMs<br>*Ngoc La, Karthik Mahadevan, Pulkit Verma, Julie Shah* |
| 10:10–10:30 | Learning Bilevel Policies from Demonstrations for Long-Horizon Planning<br>*Dillon Z. Chen, Till Hofmann, Toryn Q. Klassen, Sheila A. McIlraith* |
| 10:30–10:50 | Coffee Break |
| | **Session 2 — Learning General Policies** |
| 10:50–11:20 | **Keynote: Anders Jonsson** |
| 11:20–11:40 | [Efficient Lookahead Encoding and Abstracted Width for General Policies](https://openreview.net/pdf?id=Uow0AlUP4R)<br>*Michael Aichmüller, Simon Ståhlberg, Martin Funkquist, Hector Geffner* |
| 11:40–12:00 | [Learning Symbolic Policies from GNNs](https://openreview.net/pdf?id=9x4fh7ViN5)<br>*Martin Funkquist, Simon Ståhlberg, Hector Geffner* |
| 12:00–12:20 | [Learning General Policies for Partially Observable Deterministic Planning](https://openreview.net/pdf?id=PmDyxQh2Ij)<br>*Samridhi Kalra, Till Hofmann, Hector Geffner* |
| 12:20–12:40 | [Enhancing Generalisation in GPT-Based Planning Policies](https://openreview.net/pdf?id=ZqyigycIZU)<br>*Massimiliano Tummolo, Nicholas Rossetti, Ivan Serina, Alfonso Gerevini* |
| 12:40–13:00 | [CoSP-TL: Common-Sense Planning under Temporal Logic Constraints with LLMs](https://openreview.net/pdf?id=fB5mbQ4KBF)<br>*Emanuele Musumeci, Alessio Saladino, Elena Umili, Luca Iocchi, Daniele Nardi* |
| 13:00–14:30 | Lunch Break |
| | **Session 3 — Abstraction, Skills & Transfer in RL** |
| 14:30–15:00 | **Keynote: David Abel** |
| 15:00–15:20 | Going Beyond State-Reaching: Abstractions for Intrinsically Motivated Skill Discovery<br>*Akhil Bagaria, Anita De Mello Koch, George Konidaris* |
| 15:20–15:40 | [Structural Analogies as Posterior Transfer in Continual RL](https://openreview.net/pdf?id=ahbc5TnonS)<br>*Sole Traverso, Joshua Benjamin Evans, Henning Sprekeler, Marc Toussaint* |
| 15:40–16:00 | [Autonomous Assessment of Generalizability of AI Agent Capabilities](https://openreview.net/pdf?id=yzAneZFyMe)<br>*Daniel Richard Bramblett, Rushang Karia, Adrian Ciotinga, Pulkit Verma, YooJung Choi, Siddharth Srivastava* |
| 16:00–16:20 | Coffee Break |
| | **Session 4 — Symbolic Reasoning, Abstraction & Verification** |
| 16:20–16:40 | [Revisiting Landmarks: Generalizing over Problem Instances](https://openreview.net/pdf?id=SmeLjVXq9N)<br>*Issa Hanou, Sebastijan Dumancic, Mathijs de Weerdt* |
| 16:40–17:00 | [Abstraction via Skolemization for Generalized Planning](https://openreview.net/pdf?id=DfUfaeFIWt)<br>*Till Hofmann, Dillon Z. Chen, Toryn Q. Klassen, Sheila A. McIlraith* |
| 17:00–17:20 | [Verifinsta: Verifying If an Instance Belongs to a Domain](https://openreview.net/pdf?id=pojfiENcMg)<br>*Claudia Grundke, Gabriele Röger, Malte Helmert* |
| 17:20–17:40 | [Efficient Search by Tentatively Pruning Objects from Planning Tasks](https://openreview.net/pdf?id=Df75VCbiSO)<br>*Anita De Mello Koch, Naman Shah, Cameron Allen, George Konidaris* |
| 17:40–18:00 | [Logical Regression for Planning with Axioms](https://openreview.net/pdf?id=JPuiMksA5m)<br>*Connor Little, Christian Muise* |

</div>

## Organizing Committee

- [Akhil Bagaria](https://abagaria.github.io/), Amazon
- [Dillon Chen](https://dillonzchen.github.io/), LAAS-CNRS, University of Toulouse
- [Till Hofmann](https://ml.rwth-aachen.de/~till.hofmann/), RWTH Aachen University
- [Naman Shah](https://namanshah.net/), Allen Institute for AI (Ai2)

## Advisory Board
- Blai Bonet, Universitat Pompeu Fabra, Spain, and Universidad Simón Bolívar, Venezuela
- Giuseppe De Giacomo, University of Oxford, UK
- Hector Geffner, RWTH Aachen University, Germany
- Anders Jonsson, Universitat Pompeu Fabra, Spain
- Sheila McIlraith, The University of Toronto, Canada
- Siddharth Srivastava, Arizona State University, USA
- Peter Stone, The University of Texas at Austin, USA and Sony AI
- Sylvie Thiébaux, Australian National University, Australia and Université de Toulouse, France
- Shlomo Zilberstein, The University of Massachusetts Amherst
