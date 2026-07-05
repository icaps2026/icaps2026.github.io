---
title: "ICAPS'26 Workshop: LM4Plan"
date: 2025-04-13T00:00:00+00:00
draft: false
---

# 3rd Workshop on Planning in the Era of LLMs (LM4Plan @ ICAPS 2026)

> **Update:** Schedule and Invited Talk announced!

Visit [https://llmforplanning.github.io/](https://llmforplanning.github.io/ICAPS26/) for up-to-date information.
The workshop will take place on **June 29, 2026**.

# Overview
Language Models (LMs) are a disruptive force, changing how research was done in many subareas of AI. Planning is one of the last bastions that remain standing. The focus of this workshop is on the questions in the intersection of these areas. Some of the specific areas we would like to gain a better understanding in include: what LMs can contribute to planning, how LMs can/should be used, what the pitfalls of using LMs are and what guarantees can be obtained.

# Topics of Interest
We invite paper submissions on the following (not exhaustive) list of topics:

* Planning directly with pre-trained or fine-tuned LMs.
* Planning for LMs.
* LMs for (partial) model elicitation.
* LMs for generating structured planning problem descriptions.
* LMs for search guidance or search pruning.
* LMs for validation and verification of plans, policies, or models.
* LMs for generalization in planning and generalized planning.
* Using LMs as a proxy for user preferences.
* Using LMs to develop interfaces for planning-based systems or planning-related problems.
* Other applications of LMs in planning.

We particularly encourage submissions leveraging small and open-weight language models, especially those advancing efficient and reliable methods with rigorous, reproducible evaluations and accessible research artifacts.


# Important Dates
- Paper submission deadline: ~~May 1st, 2026, AoE~~ ~~May 8, 2026, AoE~~
- Paper acceptance notification: ~~June 2nd, 2026, AoE~~
- Workshop: **June 29, 2026**

ICAPS will be **in-person** this year. **Authors of accepted workshop papers are expected to register for the workshop, physically attend the conference and present in person.** All accepted papers will have an **oral presentation**.


# Submission Details
We solicit workshop paper submissions relevant to the above call. Paper submissions should be made through [OpenReview](https://openreview.net/group?id=icaps-conference.org/ICAPS/2026/Workshop/LM4Plan).

### Format

All submissions must be a single PDF file and follow one of the formats below:

- **Long papers** – up to 8 pages + unlimited references / appendices
- **Short papers** – up to 4 pages + unlimited references / appendices

### Style

Please format submissions in AAAI style (see instructions in the [Author Kit](https://aaai.org/authorkit26-1/) ).

### Dual-submission and non-archival policy

Authors submitting papers rejected from other conferences, please ensure you do your utmost to address the comments given by the reviewers. Please do not submit papers that are already accepted for the main ICAPS conference to the workshop. The workshop is a non-archival venue and will not have official proceedings. Workshop submissions can be subsequently or concurrently submitted to other venues.

### Double-blind Reviewing policy

All **submissions must be anonymized** and may not contain any identifying information that may violate the double-blind reviewing policy. Submissions and reviews will not be public. Only accepted papers will be made public.

# Invited Talk

## LLMs don't even need to plan — they can build planners

<img src="/img/workshops/lm4plan/jendrik.jpg"
     alt="Jendrik Seipp"
     width="220"
     style="float: right; margin: 0.2rem 0 1rem 1.5rem; border-radius: 8px;">

**[Jendrik Seipp](https://mrlab.ai/jendrik-seipp/), Linköping University**

📄 [Slides](/files/workshops/lm4plan/seipp-lm4plan2026-talk.pdf) &nbsp;·&nbsp; ▶️ [Watch the talk](https://www.youtube.com/watch?v=ECBiQsFxYpo)

### Abstract

For years, LLMs couldn't reliably solve even the smallest planning tasks. That has changed: we recently showed that the latest frontier models now beat even the strongest classical planners on several benchmark domains. Using an LLM as the planner is still rarely the best choice. Having it build planner components instead is faster, cheaper, and far less energy-hungry. I show how to do this while keeping the guarantees that make classical planning worth using, like optimality and bounded runtime. And it doesn't stop at planners. Agents can now carry out research largely on their own, and I'll close with some thoughts on what that means for how we work as researchers.

### Speaker Bio

Jendrik Seipp is a Senior Associate Professor in Artificial Intelligence at Linköping University, Sweden, where he directs the Machine Reasoning Lab within the AIICS division. His research focuses on AI planning and its connections to machine learning. He earned his MSc in computer science from the University of Freiburg, Germany (2012) and his PhD from the University of Basel, Switzerland (2018), where he then worked as a postdoctoral researcher until 2020. He joined Linköping University as an assistant professor in 2021 and was promoted to senior associate professor in 2024. His work is supported by WASP, a Swedish Research Council Starting Grant, a Wallenberg Academy Fellowship, and an SSF Future Research Leaders grant.

<div style="clear: both;"></div>

# Schedule

<style>
.lm4plan-schedule {
  --accent: #f5821f;
  --accent-soft: #fff4ea;
  --line: #ededed;
  margin: 1.5rem 0 2.5rem;
}
.lm4plan-schedule .lm4plan-day {
  margin: 0 0 .25rem;
  font-size: 1.45rem;
  color: #2b2b2b;
  border-bottom: 2px solid var(--accent);
  padding-bottom: .3rem;
}
.lm4plan-schedule .lm4plan-session {
  display: flex;
  align-items: baseline;
  gap: .6rem;
  margin: 1.9rem 0 .6rem;
}
.lm4plan-schedule .lm4plan-session .name {
  font-size: 1.12rem;
  font-weight: 700;
  color: var(--accent);
}
.lm4plan-schedule .lm4plan-session .clock {
  font-size: .9rem;
  color: #777;
  font-variant-numeric: tabular-nums;
}
.lm4plan-schedule .lm4plan-note {
  color: #666;
  font-style: italic;
  margin: .4rem 0 .9rem;
}
.lm4plan-schedule table {
  width: 100%;
  border-collapse: collapse;
  margin: .4rem 0 1.1rem;
  font-size: .92rem;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 1px 3px rgba(0, 0, 0, .07);
}
.lm4plan-schedule thead { display: none; }
.lm4plan-schedule tbody td {
  padding: .55rem .85rem;
  border-top: 1px solid var(--line);
  vertical-align: top;
  line-height: 1.4;
}
.lm4plan-schedule tbody tr:nth-child(even) { background: #faf9f8; }
.lm4plan-schedule tbody tr:hover { background: var(--accent-soft); }
.lm4plan-schedule td:first-child,
.lm4plan-schedule th:first-child {
  white-space: nowrap;
  font-weight: 700;
  color: #1a1a1a;
  font-variant-numeric: tabular-nums;
  width: 1%;
}
.lm4plan-schedule td:nth-child(2) { font-weight: 600; color: #222; }
.lm4plan-schedule td:nth-child(3) { color: #555; }
.lm4plan-schedule td:last-child,
.lm4plan-schedule th:last-child {
  text-align: center;
  white-space: nowrap;
  width: 1%;
  color: #888;
  font-size: .82rem;
  font-variant-numeric: tabular-nums;
}
.lm4plan-schedule .lm4plan-break {
  display: flex;
  align-items: center;
  gap: .5rem;
  background: var(--accent-soft);
  border-left: 4px solid var(--accent);
  padding: .55rem .9rem;
  margin: 1rem 0 1.6rem;
  border-radius: 6px;
  font-weight: 600;
  color: #8a4b12;
}
@media (max-width: 600px) {
  .lm4plan-schedule table { font-size: .82rem; }
  .lm4plan-schedule td, .lm4plan-schedule th { padding: .4rem .5rem; }
}
</style>

<div class="lm4plan-schedule">

<h3 class="lm4plan-day">Morning</h3>

<div class="lm4plan-session"><span class="name">Session 1</span><span class="clock">9:00-10:20</span></div>

<p class="lm4plan-note">9:00 — Opening remarks</p>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 9:05 | [Semantic Partial Grounding via LLMs](/files/workshops/lm4plan/1_Semantic_Partial_Grounding_v.pdf) | Giuseppe Canonaco, Alberto Pozanco, Daniel Borrajo | 15 |
| 9:20 | [Benchmarking LLM Pipelines for Natural Language to Automated Planning Models](/files/workshops/lm4plan/6_Benchmarking_LLM_Pipelines_f.pdf) | Marcus Tantakoun, Christian Muise, Xiaodan Zhu | 15 |
| 9:35 | [Grounded Evaluation and Repair for NL-to-PDDL Problem Generation](/files/workshops/lm4plan/20_Grounded_Evaluation_and_Rep.pdf) | Joana Rosa, Bruno Martins, L. Miguel Silveira, Pedro Ricardo Leitão dos Santos | 15 |
| 9:50 | [Towards LLM-Driven Synthesis of Narrative Planning Models](/files/workshops/lm4plan/17_Towards_LLM_Driven_Synthesi-1.pdf) | Allix Fletcher, Christian Muise | 15 |
| 10:05 | [A Natural Language Copilot for Interactive Plan Space Exploration](/files/workshops/lm4plan/19_A_Natural_Language_Copilot_-1.pdf) | Paul Horn, Daniel Gnad | 15 |

<div class="lm4plan-break">Coffee break - 10:30-10:50</div>

<div class="lm4plan-session"><span class="name">Session 2</span><span class="clock">10:50-12:20</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 10:50 | [FABLE: A Novel Data-Flow Analysis Benchmark on Procedural Text for Large Language Model Evaluation](/files/workshops/lm4plan/4_FABLE_A_Novel_Data_Flow_Anal.pdf) | Vishal Pallagani, Nitin Gupta, John A. Aydin, Biplav Srivastava | 15 |
| 11:05 | [ALPSBench: Can Large Language Models Reason Their Way Through Planning Formalisms?](/files/workshops/lm4plan/5_ALPSBench_Can_Large_Language.pdf) | Marcus Tantakoun, Christian Muise, Xiaodan Zhu | 15 |
| 11:20 | [On the Ability of Transformers to Verify Plans](/files/workshops/lm4plan/10_On_the_Ability_of_Transform.pdf) | Yash Sarrof, Yupei Du, Katharina Stein, Alexander Koller, Sylvie Thiebaux, Michael Hahn | 15 |
| 11:35 | [Toward a General Framework for Evaluating Per-Domain Generalization Using LLMs, Theorem Provers, and Statistical Model Checking](/files/workshops/lm4plan/12_Toward_a_General_Framework_-1.pdf) | Nicola J. Müller, Naya Rudolph, Ayal Taitler, Timo P. Gros | 15 |
| 11:50 | [Integrating the Unified Planning Framework via MCP with Large Language Models for Reliable Automated Planning](/files/workshops/lm4plan/8_Integrating_the_Unified_Plan.pdf) | João Areias Saraiva, Thomas Kirste | 15 |
| 12:05 | [Learning HTNs from Visual Demonstration with Vision-Language Models: Preliminary Results](/files/workshops/lm4plan/7_Learning_HTNs_from_Visual_De.pdf) | Ngoc La, Karthik Mahadevan, Pulkit Verma, Julie Shah | 15 |

<div class="lm4plan-break">Lunch break - 12:30-14:00</div>

<h3 class="lm4plan-day">Afternoon</h3>

<div class="lm4plan-session"><span class="name">Session 3</span><span class="clock">14:00-15:15</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 14:00 | [LLM-Evolved Domain-Independent Heuristics for Symbolic AI Planning](/files/workshops/lm4plan/9_LLM_Evolved_Domain_Independe.pdf) | Elliot Gestrin, Jendrik Seipp | 15 |
| 14:15 | [Personalized Medication Planning via Direct Domain Modeling and LLM-Generated Heuristics](/files/workshops/lm4plan/16_Personalized_Medication_Pla.pdf) | Yonatan Vernik, David Izhaki, Alexander Tuisov, Hana Weitman, Alexander Shleyfman, Gal Kaminka | 15 |
| 14:30 | [Learning and Reusing Policy Decompositions for Hierarchical Generalized Planning with LLM Agents](/files/workshops/lm4plan/11_Learning_and_Reusing_Policy.pdf) | Shirin Sohrabi, Haritha Ananthakrishnan, Harsha Kokel, Kavitha Srinivas, Michael Katz | 15 |
| 14:45 | [Think Hierarchically, Act Optimally: Decoupled Hierarchical Planning and Execution for LLM Agents](/files/workshops/lm4plan/18_Think_Hierarchically_Act_Op.pdf) | Vikas Kumar, Jyotsana Khatri, Shirish Karande | 15 |
| 15:00 | [The Curious Case of Planning for Unreliable Agents: Challenges and Opportunities in Orchestrating Generative AI Agents](/files/workshops/lm4plan/14_The_Curious_Case_of_Plannin.pdf) | Roya Daneshi, Sunandita Patra, Kshama Dwarakanath, Sriram Gopalakrishnan, Daniel Borrajo, Sarath Sreedharan | 15 |

<div class="lm4plan-break">Coffee break - 15:30-15:50</div>

<div class="lm4plan-session"><span class="name">Session 4</span><span class="clock">15:50-17:30</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 15:50 | Invited talk: [LLMs don't even need to plan — they can build planners](/files/workshops/lm4plan/seipp-lm4plan2026-talk.pdf) ([video](https://www.youtube.com/watch?v=ECBiQsFxYpo)) | Jendrik Seipp | 50 |
| 16:40 | Panel discussion and closing remarks |  | 50 |

</div>

<small>Talk length is shown in the last column in minutes. Paper talks are 10 min presentation + 5 min Q&A.</small>


# Accepted Papers

- **Semantic Partial Grounding via LLMs**\
  *Giuseppe Canonaco, Alberto Pozanco, Daniel Borrajo*
- **FABLE: A Novel Data-Flow Analysis Benchmark on Procedural Text for Large Language Model Evaluation**\
  *Vishal Pallagani, Nitin Gupta, John A. Aydin, Biplav Srivastava*
- **ALPSBench: Can Large Language Models Reason Their Way Through Planning Formalisms?**\
  *Marcus Tantakoun, Christian Muise, Xiaodan Zhu*
- **Benchmarking LLM Pipelines for Natural Language to Automated Planning Models**\
  *Marcus Tantakoun, Christian Muise, Xiaodan Zhu*
- **Learning HTNs from Visual Demonstration with Vision-Language Models: Preliminary Results**\
  *Ngoc La, Karthik Mahadevan, Pulkit Verma, Julie Shah*
- **Integrating the Unified Planning Framework via MCP with Large Language Models for Reliable Automated Planning**\
  *João Areias Saraiva, Thomas Kirste*
- **LLM-Evolved Domain-Independent Heuristics for Symbolic AI Planning**\
  *Elliot Gestrin, Jendrik Seipp*
- **On the Ability of Transformers to Verify Plans**\
  *Yash Sarrof, Yupei Du, Katharina Stein, Alexander Koller, Sylvie Thiebaux, Michael Hahn*
- **Learning and Reusing Policy Decompositions for Hierarchical Generalized Planning with LLM Agents**\
  *Shirin Sohrabi, Haritha Ananthakrishnan, Harsha Kokel, Kavitha Srinivas, Michael Katz*
- **Toward a General Framework for Evaluating Per-Domain Generalization Using LLMs, Theorem Provers, and Statistical Model Checking**\
  *Nicola J. Müller, Naya Rudolph, Ayal Taitler, Timo P. Gros*
- **The Curious Case of Planning for Unreliable Agents: Challenges and Opportunities in Orchestrating Generative AI Agents**\
  *Roya Daneshi, Sunandita Patra, Kshama Dwarakanath, Sriram Gopalakrishnan, Daniel Borrajo, Sarath Sreedharan*
- **Personalized Medication Planning via Direct Domain Modeling and LLM-Generated Heuristics**\
  *Yonatan Vernik, David Izhaki, Alexander Tuisov, Hana Weitman, Alexander Shleyfman, Gal Kaminka*
- **Towards LLM-Driven Synthesis of Narrative Planning Models**\
  *Allix Fletcher, Christian Muise*
- **Think Hierarchically, Act Optimally: Decoupled Hierarchical Planning and Execution for LLM Agents**\
  *Vikas Kumar, Jyotsana Khatri, Shirish Karande*
- **A Natural Language Copilot for Interactive Plan Space Exploration**\
  *Paul Horn, Daniel Gnad*
- **Grounded Evaluation and Repair for NL-to-PDDL Problem Generation**\
  *Joana Rosa, Bruno Martins, L. Miguel Silveira, Pedro Ricardo Leitão dos Santos*

# Organizing Committee

- Augusto B. Corrêa, University of Oxford
- Elliot Gestrin, Linköping University
- Michael Katz, IBM
- Nir Lipovetzky, University of Melbourne
- Luckeciano C. Melo, University of Oxford
- Sarath Sreedharan, Colorado State University
- Katharina Stein, Saarland University

Please send your inquiries to [llmforplanning@gmail.com](mailto:llmforplanning@gmail.com)
