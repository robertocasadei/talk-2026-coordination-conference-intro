---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /imgs/banner2026.png # https://cover.sli.dev
# some information about your slides (markdown enabled)
layout: cover
title: COORDINATION 2026
# info provides ..
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
# duration of the presentation
duration: 5min

---

<style>
#slidev-goto-dialog {
  display: none !important;
  visibility: hidden !important;
  pointer-events: none !important;
}
</style>

# Welcome to COORDINATION 2026

---
zoom: 0.9
---

# COORDINATION 2026 - Aims, Scope, Topic

*Aims &amp; scope:* be the main forum for research on theory and practice of coordination (the ruling of interaction among distributed components)

*Topics:* (revised this year)

1. **Theoretical models and foundations for coordination**
    - concurrency, semantics, logic, probabilistic, formal methods
2. **Coordination Paradigms &amp; Languages**
    - choreography, orchestration, actors, agents, swarms, AI/ML
3. **Distributed &amp; Pervasive &amp; Modern Computing**
    - services, HPC, CPS, IoT, edge/fog/cloud, pervasive/ubiquitous, decentralised computing 
4. **Software Engineering &amp; Applications for Coordinated Systems**
    - languages, architectures, methodologies, patterns, DevOps, digital twins, GenAI/LLM
5. **Cross-Cutting and Multi-/Inter-/Trans-Disciplinary Aspects**
    - dependability, security, adaptation, interdisciplinary/societal aspects 
6. **Coordination Platforms, Middleware, and Tools** 
    - simulation, DSLs, V&amp;V, platforms, datasets, benchmarks

---
zoom: 0.65
---

# COORDINATION 2026 - Programme

<style>
h4 { color: #a00; }
</style>

<div v-click.fade>

#### Mon, June 8, 14:00 - **COORDINATION tutorial**



* Distributed Runtime Verification in Proximity-based Networks: A Tutorial on the Aggregate Programming Approach (Audrito, Damiani, Scarso, Stolz, Torta)

</div>

<div v-click.fade>

#### Tue, June 9, 09:00 - **COORDINATION INVITED TALK**

- Efficient Communication and Coordination in Multiagent Reinforcement Learning (Mehdi Dastani)

</div>

<div v-click.fade>

#### Tue, June 9, 10:30 -  **Formal modeling and analysis of distributed systems** (chair: C. Talcott)

- Timed Scenario Expressions and Realisability
- HistMSO: a Logic for Reasoning on Consistency Models with MONA
- Motif Refinement for the Hierarchical Control of Structured CPSs

#### Tue, June 9, 14:00 - **Formal verification in coordination languages** (chair: I. Lanese)
 
- Deductive Verification of Legal Contracts
- Proof of Delivery: Mechanized Mailbox Types

#### Tue, June 9, 15:30 - **Distributed algorithms for collective adaptive systems** (chair: TBD)
 
- Aggregate Indoor Localisation
- A Self-Stabilizing Min-Max Consensus via Path-loop Detection

</div>

<div v-click.fade>

#### Wed, June 10, 10:30 - **BEST PAPER SESSION**

- Runtime adaptation as a programming pattern in service composition

</div>

<div v-click.fade>

#### Wed, June 10, 15:30 - **Simulation tools and methodologies for collective adaptive systems** (chair: G. Audrito)

- Simulation and Analysis of Indoor-Air-Quality Measuring Devices with YODA
- High-Fidelity Simulation of Aggregate Computing Systems with Collektivity

</div>

<div v-click.fade>

#### Thu, June 11, 10:30 - **Coordination languages, frameworks, and foundations** (chair: S. Bliudze)

- ScalaTropy: Multiparty Coordination with Monadic Communication Primitives
- Bach4Popper: Towards Federated Inductive Logic Programming using Coordination
- Phyelds: A Pythonic Framework for Aggregate Computing 

</div>

---

# COORDINATION 2026 - Invited Talk

When: Tuesday, June 9th, 9am

Title: **Efficient Communication and Coordination in Multiagent Reinforcement Learning**

Author: **Mehdi Dastani** (Utrecht University, The Netherlands)

Abstract: Multiagent reinforcement learning (MARL) is a powerful framework for learning effective policies in complex multiagent environments. A key challenge in MARL is to learn coordinated policies efficiently in a decentralised manner. Prior work has explored a range of communication and coordination mechanisms to address these challenges.
In this talk, I will present our recent contributions towards improving the efficiency and performance of MARL systems through principled communication and coordination mechanisms. First, I introduce a decentralised communication scheduling approach that leverages supervised learning to construct a message estimation model. This model enables individual agents to selectively decide when sharing local information is beneficial, thereby reducing unnecessary communication. Empirical results show that this approach significantly decreases communication overhead while improving overall learning performance. Second, I present two logic-based methods for synthesising multiagent reward machines and action-masking artefacts. These methods provide formal guarantees that the resulting policies are both coordinated and safe, while also improving sample efficiency.

---
zoom: 0.95
---

# COORDINATION 2026 - Invited Tutorial

When: Monday, June 8th, 14

Title: **Distributed Runtime Verification in Proximity-based Networks: A Tutorial on the Aggregate Programming Approach**

Authors: Giorgio Audrito, Ferruccio Damiani, Giordano Scarso, Volker Stolz, Gianluca Torta

Abstract:  Distributed runtime verification (DRV) addresses the problem
of checking the correctness of distributed systems during execution,
coping with partial knowledge, dynamic topologies, and the absence of
global time. These challenges are particularly prominent in
proximity-based networks, such as those arising in IoT and Far Edge
computing scenarios, where large numbers of devices interact through
local communication.  This tutorial presents an approach to DRV based on
Aggregate Programming (AP), a paradigm for designing distributed
collective systems via high-level abstractions over computational
fields. We show how temporal and spatial properties (expressed in
past-CTL and SLCS, respectively) can be systematically compiled into
aggregate monitors grounded in the eXchange Calculus and executed using
the FCPP C++ framework and simulator for AP. The tutorial combines
conceptual foundations with practical guidance: participants learn how
to specify spatio-temporal properties, generate corresponding monitors,
and execute them in a 3D simulation environment. Examples are drawn from
ongoing industrial collaborations and research projects, which we use to
illustrate realistic monitoring scenarios and motivate open challenges
for AP-based DRV.

---

# COORDINATION 2026 - Proceedings

* The proceedings are **almost ready**
* Check-out the [COORDINATION website](https://www.discotec.org/2026/coordination) for:
    * the link to the [official proceedings web page](https://link.springer.com/book/9783032283573)
    * the link to the **[PDF of the (uncorrected) proceedings book](https://drive.google.com/file/d/13XxArDW5dJTOiQtUDXA67sVPq0OE-9V8/view?usp=sharing)**

---

# COORDINATION 2026 - Special Issues

* For papers: **Special Issue on the Logical Methods in Computer Science (LMCS) journal**
    * a selected number of authors/papers will be invited shortly after the conference
    * 4-6 months for producing the extended version
* For artefacts: **Special Issue on the Science of Computer Programming (SCP) journal - Track on Original Software Publications (OSP)**
    * we are working on this

---

# COORDINATION 2026 - Analytics of Submission

- We had **30 paper** submissions: 
	- 2 were desk-rejected;
	- 23 regular and 5 tool papers sent for the review
- We had **13 artifact** submissions
		
<!--![Geographical distribution of submissions](/)-->

<img src="/imgs/num-submission-by-country.png" style="width:65%; margin-left: auto; margin-right: auto;" >

---

# COORDINATION 2026 - Analytics of Review

- We had **32 PC members** from **15 different countries** (with gender balance **F/M = 12/20**)
- We had **9 members** of the Artifact Evaluation Committee (AEC), chaired by Gianluca Aguzzi

<!--![Review process](/imgs/num-reviewers-per-submissions.png)-->

<img src="/imgs/num-reviewers-per-submissions.png" style="width:65%; margin-left: auto; margin-right: auto;" >

---

# COORDINATION 2026 - Analytics of acceptance rate
- 13 out of 28 papers were accepted (**46%**): 11 regular and 2 tool papers
- 7 artifacts awarded __*Available and Functional*__ Badge (of which, 3 also the __*Reusable*__ badge)
<!--![Geographical distribution of submissions](/imgs/number-submission-acceptance-by-country.png)-->

<img src="/imgs/number-submission-acceptance-by-country.png" style="width:70%; margin-left: auto; margin-right: auto;" >

---

# COORDINATION 2026 - Acknowledgements

- We warmly thank the **Steering Commitee** and especially its chair **Michele Loreti** for the support in organising the conference
- We warmly thank the DisCoTec general chair  **Claudio Mezzina** for various other organisational aspects
- We warmly thank the **Program Committee members** for the review and discussion activity (great service!)
- We also warmly thank all the **COORDINATION submitters, authors, and participants** for contributing to the conference!

---
zoom: 0.8
---

# COORDINATION 2026 - Have a great time at the conference!

&nbsp;

We hope you will enjoy the COORDINATION program and community!

<div class="grid grid-cols-2 gap-8 items-center">
  <div class="w-[60%] aspect-[3/4] overflow-hidden justify-self-center">
    <img src="/imgs/roby.png" class="w-full h-[90%] object-cover object-center scale-80" />

    Roberto
  </div>
  <div class="w-[60%] aspect-[3/4] overflow-hidden justify-self-center">
    <img src="/imgs/fatemeh.jpg" class="w-full h-[90%] object-cover object-center scale-80" />

    Fatemeh
  </div>
</div>
