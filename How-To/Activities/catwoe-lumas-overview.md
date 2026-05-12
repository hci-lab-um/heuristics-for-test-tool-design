# CATWOE and LUMAS: An Overview of Soft Systems Frameworks

> *This document was produced with the assistance of Claude Sonnet 4.6 by Anthropic.*

---

## Contents

- [What Is Soft Systems Methodology?](#what-is-soft-systems-methodology)
- [The LUMAS Framework](#the-lumas-framework)
- [The CATWOE Framework](#the-catwoe-framework)
- [How LUMAS and CATWOE Work Together](#how-lumas-and-catwoe-work-together)
- [Victims and Beneficiaries](#victims-and-beneficiaries)
- [Applying CATWOE](#applying-catwoe)
- [Strengths and Limitations](#strengths-and-limitations)
- [Relevant Figures and Diagrams](#relevant-figures-and-diagrams)
- [Comparison Table: CATWOE/LUMAS and idea-t](#comparison-table-catwoe-lumas-and-idea-t)
- [Glossary](#glossary)
- [Abbreviations](#abbreviations)
- [References](#references)

---

## What Is Soft Systems Methodology?

Soft Systems Methodology (SSM) was developed by Peter Checkland as an approach to understanding and managing *messy situations* [37] — complex, real-world problems where there is no single right answer and where different people have genuinely different views of both the problem and the solution.

The core idea is this: complex problems in organisations are never static. They involve multiple interacting views of reality, held by different people with different assumptions about the world. As Checkland puts it, all problematic situations contain "people who are trying to act purposefully, with intention" [37] — and those people will not all see the problem, or the solution, in the same way.

SSM offers a structured way to work with this complexity. Rather than seeking *the* right answer, SSM supports negotiating a good enough solution that fits the different world views of the people involved. The role of the systems engineer shifts from providing a single correct solution to facilitating a workable one.

SSM was an early example of putting people and their world views at the centre of thinking about information systems — well before *human-centred design* became mainstream terminology. In comparison with more technical approaches to systems design, SSM asserts that "hard" systems engineering can fail to meet people's needs by not considering *who* has a viewpoint [37].

Checkland provides two complementary frameworks within SSM: **LUMAS** and **CATWOE**.

---

## The LUMAS Framework

**LUMAS** stands for:

| Letter | Word | Meaning |
|--------|------|---------|
| **L** | Learning | Insight gained from examining the current situation |
| **U** | User | The person at the centre of the transformation |
| **M** | Methodology | The structured approach being applied |
| **A** | Approach | The tailored way the methodology is applied in this context |
| **S** | Situation | The real-world state of affairs — before and after change |

LUMAS describes an iterative cycle of change:

1. A **Real World Situation** exists — something that needs attention
2. Examining it produces **Learning**
3. Learning informs and modifies the choice of **Methodology**
4. The methodology is tailored into a specific **Approach** for this situation
5. Applying the approach leads to a new **Real World Situation**

The **User** of the methodology sits at the centre of this cycle, not at the edge of it. The framework makes explicit that the person doing the work — and experiencing the situation — is central to the process of change, not merely an observer of it.

![Soft Systems LUMAS Model Based on [37] Dissertation Figure 7.2, page 123](../../Figures/softsystems2.jpg)



---

## The CATWOE Framework

**CATWOE** stands for:

| Letter | Word | Meaning |
|--------|------|---------|
| **C** | Customers | Those who are affected by the transformation — for better or worse |
| **A** | Actors | Those who carry out the transformation activities |
| **T** | Transformation Process | What is being changed — the core activity |
| **W** | Worldviews | The different perspectives people bring; why the transformation makes sense to each of them |
| **O** | Owners | Those with the authority to stop the transformation |
| **E** | Environmental Constraints | External factors that limit or shape what is possible |

CATWOE is used to decide on **purposeful activities** to make interventions and cause change. Once you have decided what to do and how to do it (from LUMAS), CATWOE enriches understanding of the change activities themselves.

The framework is not taken in alphabetical order. It is worked through as **T → W → C → A → O → E**: first define the transformation and world view, then consider customers, actors, owners, and environmental constraints [37].

![Soft Systems CATWOE Model Based on [37] Dissertation Figure 7.3, page 124](../../Figures/softsystems4.jpg)


---

## How LUMAS and CATWOE Work Together

LUMAS and CATWOE are complementary — they address different aspects of the same challenge.

**LUMAS** provides the iterative *cycle* of change — the learning loop. It keeps the User at the centre and focuses on *how* the methodology is applied in context.

**CATWOE** enriches the *content* of the change — the *who* and *what*. It identifies all the different people involved, their different roles, and the constraints on what can be achieved.

The **User** in LUMAS becomes a more detailed and nuanced set of *people* in CATWOE: the same person might be a Customer (affected by the change), an Actor (carrying it out), or an Owner (with authority over it) — and possibly all three at different times.

![Soft Systems People in LUMAS and CATWOE Models Based on [37] Dissertation Figure 7.4, page 124](../../Figures/users-in-lumas-and-catwoe.jpg)



Together, LUMAS and CATWOE form part of a wider thinking process. The CATWOE analysis, for example, leads to:

- A **root definition** of the problem
- Identification of **primary tasks** and **purposeful activities**
- Recognition of the multiple roles people play and whether they experience the change as a benefit or a burden

---

## Victims and Beneficiaries

One of the most practically useful concepts in CATWOE is the explicit recognition that the same change can be experienced very differently by different people. Checkland notes that people can be **adversely affected** by a system or improvements to a system — not just positively — and he characterises this distinction as **victims** and **beneficiaries** [37].

This is not a trivial point. When a new tool or process is introduced:

- One person might experience it as a **benefit** — it makes their work easier, more efficient, or more fulfilling
- Another person might experience themselves as a **victim** — their job skills are devalued, their workload increases, or they feel imposed upon

Both responses are legitimate and need to be understood when planning change. The same system change, viewed from different world views, can be experienced in completely opposite ways.

For example: a tester asked to adopt test automation tools might see this as freeing them from repetitive work, allowing more time for complex, interesting testing. Or they might see it as a threat to their job security, with their established skills becoming less valued. Both world views are real.

The CATWOE principle is: *everyone is right from their own point of view*. Effective change requires understanding all the world views in play, not just the ones that are visible or loudly expressed.

---

## Applying CATWOE

CATWOE provides a method for defining the problem and partial solution clearly before acting:

1. Identify the **need to achieve result R**
2. Identify the **action P** required
3. Identify the **method Q** to take that action
4. Enrich the understanding by working through **C, A, T, W, O, E**

This leads to a primary task definition and purposeful activity, grounded in a clear understanding of who is involved, what they are trying to achieve, and what constraints apply.

![Soft Systems Applying CATWOE Framework Based on [37] Dissertation Figure 7.5, page 125](../../Figures/softsystems3.jpg)

---

## Strengths and Limitations

**Strengths:**
- Puts people at the centre of systems thinking — explicitly recognises multiple, legitimate world views
- Provides a structured way to work with complex, messy problems where there is no single right answer
- The concepts of victims and beneficiaries are practically valuable — they surface tensions and resistances that purely technical approaches miss
- Works iteratively — supports learning and adaptation as understanding develops
- Applicable to any transformation involving people and organisations

**Limitations:**
- The Transformation and Worldview elements are defined before the Customer, Owner, or Actors in the standard CATWOE sequence — this can appear to prioritise organisational vision over practitioner viewpoints. It is not entirely clear from the framework itself whether the Transformation element encapsulates the goal (Why?) or whether the whole framework is action-oriented
- SSM originated in academic systems thinking and can require some effort to learn and apply in fast-moving practical settings
- Like the Zachman Framework, it is descriptive rather than prescriptive — it helps you understand, but does not tell you exactly what to do

---

---

## Comparison Table: CATWOE/LUMAS and idea-t

The table below, drawn from the dissertation's research modelling, shows how the concepts in CATWOE and LUMAS map to areas of the idea-t framework. This is included here for reference, not as a guide to using idea-t — see the idea-t documentation for that - but it does indicate which heuristics might help address parts of this model if it is used.

*Table 12.4 — Comparing idea-t to Soft Systems CATWOE and LUMAS (from research modelling)*

| CATWOE/LUMAS Element | idea-t Theme | idea-t Heuristics | Notes |
|---------------------|-------------|-------------------|-------|
| Customers | Who? | H02–H06 | Customer as stakeholder for change |
| Actors | Who? | H02–H06 | Different actors, victims and beneficiaries |
| Transformation Process | *(not yet explicit)* | — | May require adding a 'How?' theme to idea-t |
| Worldviews | Why? | H01 | Make explicit in idea-t |
| Owners | Who? | H02–H06 | Make explicit different actors |
| Environmental Constraints | Context? | H07 | Context as constraint to change |
| Learning | Why? | H01 | Make explicit learning from change |
| User | Who? | H02–H06 | Different users, victims and beneficiaries |
| Methodology | Why? | H01 | Make explicit methodology for change |
| Approach | Why? | H01 | Make explicit approach for change |
| Situation | Why? | H01 | Make explicit 'before and after' situations |

---

## Glossary

**Soft Systems Methodology (SSM)**
An approach to understanding and managing complex, real-world situations where there are multiple perspectives and no single right answer. Developed by Peter Checkland. SSM acknowledges that different people have genuinely different views of both problems and solutions.

**Transformation**
In the context of CATWOE, a transformation is a change — the process of converting a current state into a desired future state. It is the core of what CATWOE analyses.

**World View (Weltanschauung)**
The underlying assumptions, values, and beliefs through which a person interprets the world. In SSM, different people have different world views, and these differences are treated as real and legitimate, not as misunderstandings to be corrected.

**Victims and Beneficiaries**
A CATWOE concept: any change affects people differently. A beneficiary gains from the change; a victim is adversely affected by it. Both responses are legitimate and must be understood when planning change.

**Messy Situations**
A term used by Checkland to describe complex, real-world problems that are never static, involve multiple interacting perceptions of reality, and cannot be solved by a single correct technical answer.

**Root Definition**
In SSM, a concise statement that captures the essential nature of a system — what it does, for whom, and in what context. CATWOE analysis helps construct a root definition.

**Purposeful Activity**
Actions taken with intention toward a defined goal. SSM focuses on understanding and coordinating the purposeful activities of people involved in a transformation.

**Ontology**
See Zachman Framework overview document. In SSM, the focus is on people's experienced reality rather than a formal ontology of the enterprise.

---

## Abbreviations

| Abbreviation | Meaning |
|-------------|---------|
| SSM | Soft Systems Methodology |
| CATWOE | Customer, Actor, Transformation Process, Worldviews, Owners, Environmental Constraints |
| LUMAS | Learning, User, Methodology, Approach, Situation |
| IS | Information Systems |

---

## References

**Primary source:**

[37] P. Checkland and J. Poulter, “Soft systems methodology,” in Systems Approaches
to Making Change: A Practical Guide, Springer, 2020, pp. 201–253 *(Primary source for Soft Systems Methodology, LUMAS, and CATWOE.)*

Also useful but not directly referenced: P. Checkland, *Systems Thinking, Systems Practice*. Chichester: Wiley, 1981 (and subsequent editions). 



---

*Isabel Evans | 12 May 2026 | Summary extracted from PhD Dissertation. Copyrights for the described frameworks remain with the framework owners.*
