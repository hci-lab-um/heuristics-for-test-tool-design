# The Zachman Framework: An Overview

> *This document was produced by summarising a section of Isabel's dissertation with the assistance of Claude Sonnet 4.6 by Anthropic.*

---

## Contents

- [What Is the Zachman Framework?](#what-is-the-zachman-framework)
- [Structure: The Matrix](#structure-the-matrix)
- [The Six Questions (Columns)](#the-six-questions-columns)
- [The Six Levels (Rows)](#the-six-levels-rows)
- [How to Use It](#how-to-use-it)
- [Strengths and Limitations](#strengths-and-limitations)
- [How the Framework Evolved](#how-the-framework-evolved)
- [Relevant Figures and Diagrams](#relevant-figures-and-diagrams)
- [Glossary](#glossary)
- [Abbreviations](#abbreviations)
- [References](#references)

---

## What Is the Zachman Framework?

The Zachman Framework™ is a tool for thinking about, describing, and planning the architecture of an enterprise — that is, any large organisation or complex system. It was created by John A. Zachman and has been in development for more than 40 years. It began as a framework for information systems architecture and has since broadened into a general framework for enterprise architecture.

Its owners describe it as an **ontology** — a comprehensive description of everything that exists in an enterprise — rather than a **methodology** (a set of instructions for doing things). Think of the difference between a map and a route planner: the Zachman Framework is the map; it shows you everything that is there, but it does not tell you which path to take.

The framework is described as a *tool for thinking* that provides a logical and comprehensive description of an enterprise [222]. Its foundation lies in the architecture of buildings and industrial products, and it is intended as a **descriptive** representation, not a prescriptive one — it describes what is there, rather than telling you what to do.

---

## Structure: The Matrix

The Zachman Framework is organised as a **matrix**: a grid of rows and columns. Each cell in the grid represents one specific aspect of the enterprise. Every cell is independent — one fact in one place. Note: The full Zachman Framework diagram is referenced in the dissertation footnote as available at:
`https://zachman-feac.com/images/ZI_PIcs/ZF3.jpg` but this URL has not been verified as currently live; a diagram is available on the Wikipedia Zachman Framework page.

![Simplified Schematic of Zachman Framework™ Adapted from [222] Dissertation Figure 7.1, page 122](../../Figures/SimplifiedZachman.jpg)

The matrix currently has up to **36 cells** (six columns × six rows), covering every area of planning, discussion, and action for an enterprise [223]. It has grown over the years: it started with 15 cells and expanded as the framework broadened from information systems to enterprise-level thinking.

---

## The Six Questions (Columns)

The columns of the matrix are based on the classic **5W's and H** questioning framework — six fundamental questions that can be asked about any subject:

| Column | Question | What It Covers |
|--------|----------|----------------|
| 1 | **What?** | Things — the data, materials, inventory |
| 2 | **How?** | Processes — the functions and activities |
| 3 | **Where?** | Locations — where things happen |
| 4 | **Who?** | People — responsibility and organisation |
| 5 | **When?** | Timing — schedules and events |
| 6 | **Why?** | Motivation — goals, strategy and rules |

The *Who?*, *When?* and *Why?* columns were added later, as the framework moved from information systems to enterprise-level thinking. The Zachman website notes that when the framework was first published for information systems, "there was no precedent set for thoughts about Responsibility (Column 4), Timing (Column 5) or Motivation (Column 6)" [222]. The dissertation author notes this is a curious omission, since Who? When? and Why? seem essential questions even for information systems planning.

---

## The Six Levels (Rows)

The rows represent different levels of the enterprise, from high-level strategic thinking down to actual implementation:

| Row | Level | Who Works Here | Focus |
|-----|-------|---------------|-------|
| 1 | **Executive / Scope / Context** | Senior leaders | Strategy, boundaries, scope |
| 2 | **Business Manager / Concepts** | Business managers | Business concepts and goals |
| 3 | **Architect / System Logic** | Architects | System design and logic |
| 4 | **Engineer / Technology** | Engineers | Technology specifications |
| 5 | **Technician / Components** | Technicians and implementers | Specific tools and components |
| 6 | **Enterprise / Operations** | The whole organisation | The live, operating enterprise |

The rows move from **identification** (Row 1, strategic/scope) through **definition**, **representation**, **specification**, and **configuration**, down to **instantiation** — the actual running enterprise [222].

There is no fixed order for working through the matrix. It can be used top to bottom, bottom to top, or left to right. The framework simply provides the complete picture; the user decides where to start and how to move through it [223].

---

## How to Use It

The Zachman Framework does not tell you what to do — it tells you what questions to ask and what aspects to consider. Each cell in the matrix requires its own analysis and action [223]. The intent is that by working through the relevant cells, you gain a comprehensive and coherent understanding of the enterprise.

It is used as a **description artefact**: it can be used to model a prescriptive methodology in context, but it is not a methodology itself. You can align it with whatever working methods your organisation already uses.

The framework is intended to be **simple**: its owners emphasise that it should be as clear and non-technical as possible. The emphasis throughout its history has been on keeping it usable by both technical and non-technical people.

---

## Strengths and Limitations

**Strengths:**
- Comprehensive — covers all aspects of an enterprise in a single view
- Flexible — no prescribed order of use
- Descriptive — works alongside any methodology
- Long-established and well-tested in practice
- Evolves through use: its history has been one of iterative improvement following experience in industry [222]

**Limitations:**
- With up to 36 cells, it can appear challenging to apply in full
- It has been critiqued for not giving sufficient guidance on scoping the effort needed for enterprise architecture, and for not directing practitioners on how to align an organisation's transformation practices to move from the current state to the envisioned future state [223]
- A survey of architecture frameworks notes it is most suitable for manufacturing enterprises [224]
- It does not drive or enforce change — it describes; acting on that description requires additional method

---

## How the Framework Evolved

The Zachman Framework has developed over more than 40 years [222]:

- It began as a framework for **information systems (IS) architecture**, published in the IBM Systems Journal in 1987
- It evolved into a framework for **enterprise architecture**, as it became clear that the questions applied more broadly than IS alone
- The *Who?*, *When?*, and *Why?* columns were added in later versions as the scope widened
- The number of cells grew from 15 to the current 36
- Its evolution has been driven by experience in use and review with industry practitioners and academics — a pattern of iterative improvement that continues

---


## Glossary

**Enterprise Architecture (EA)**
A structured description of an organisation (enterprise) — its strategy, processes, information, technology, and people — and how they all fit together.

**Framework**
A structure that organises thinking about a subject. The Zachman Framework is a descriptive framework (it describes what is there) rather than a methodological framework (which would tell you what to do).

**Ontology**
In this context, a comprehensive formal description of everything that exists within a defined domain — in this case, the enterprise. An ontology describes what exists; a methodology describes what to do.

**Methodology**
A structured set of practices or procedures for doing work. The Zachman Framework is deliberately not a methodology.

**Reification**
The process of making something abstract more concrete. The Zachman Framework provides reification of answers to the six questions through identification, definition, representation, specification, configuration, and instantiation.

**5W's and H**
The questioning framework *Who? Why? Where? What? When? How?* — used across journalism, education, and management as a starting point for investigation. Forms the basis of the Zachman Framework's six columns.

---

## Abbreviations

| Abbreviation | Meaning |
|-------------|---------|
| EA | Enterprise Architecture |
| IS | Information Systems |
| 5W's and H | 5 W's and an H Framework (Who? Why? Where? What? When? How?) |

---

## References

**Primary source:**

[222] J. A. Zachman, *About the Zachman Framework*, Accessed (9 April 2025), 2025. [Online]. Available: https://zachman-feac.com/zachman/about-the-zachman-framework
***Note: This specific URL was not confirmed as live during link checking (May 2026). The zachman-feac.com domain is active; and there is a description of the [Zachman Framework on Wikipedia](https://en.wikipedia.org/wiki/Zachman_Framework).***

**Supporting references:**

[223] M. de Vries, "A framework for understanding and comparing enterprise architecture models," *Management Dynamics*, vol. 19, no. 2, pp. 17–29, 2010.


[224] S. R. Mary and P. Rodrigues, "Survey and comparison of frameworks in software architecture," in *Advances in Computing and Communications: First International Conference, ACC 2011*, Springer, 2011, pp. 9–18.

**Additional Zachman resource referenced in dissertation:**

Evolution of the Zachman Framework: https://zachman-feac.com/the-zachman-framework-evolution *(Confirmed live, May 2026)*

---

*Isabel Evans | 12 May 2026 | Summary extracted from PhD Dissertation. Copyrights for the described frameworks remain with the framework owners.*
