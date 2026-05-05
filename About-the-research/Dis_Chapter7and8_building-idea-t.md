# Building idea-t — A Framework of Heuristics to Aid Test Tool Design and Evaluation

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

Claude produced this 500-word summary of chapters 5 and 6 of the dissertation:

<details close><summary>500-word precis</summary>
  
The two discovery studies (Chapters 7 and 8) established that testing tools frequently fail the people using them, and that testers are a far more diverse group than stereotypes suggest. The next challenge was to turn those findings into something practically useful: a framework that could help tool designers and purchasers make better decisions. Chapters 7 and 8 describe how that framework — **idea-t** ("Influencing the Design, Evaluation and Acquisition of Tools for Testing") — was built.

**Chapter 7** covers the development work. A key early decision was to use **heuristics** — question-based rules of thumb — rather than a fixed set of personas or a prescriptive checklist. Testers are too diverse, and contexts too varied, for a one-size-fits-all approach. Heuristics already familiar in software testing and UX practice (such as Nielsen's Ten Heuristics [138]) offer a recognised, flexible format. The "shape" of the heuristics — whether they should be textual, pictorial, or conceptual; and whether they should ask, prompt, or tell — was investigated through a small pilot study with five UX practitioners. The result was a clear preference for **textual, question-style heuristics**. Starting from 153 candidate questions derived from research data, iterative expert reviews with 28 participants over nine prototype versions produced a refined set of **twelve heuristic questions**, ready for testing in industry case studies.

**Chapter 8** describes the idea-t framework in full. The twelve heuristics divide into three themes: **Why?** (one heuristic about purpose), **Who?** (five heuristics about the people who will use or be affected by the tool), and **Context?** (six heuristics about where, when, and how the tool will be used). Each heuristic is supported by a keyword, sub-questions, explanatory guidelines, research evidence, suggested activities, and links to **ISO 25010 quality attributes**. The framework is explicitly designed to help overcome the three illusions of usability identified in Chapter 5: it pushes designers and purchasers beyond attractive interfaces, beyond usability alone, and beyond the assumption of a static, stereotypical user.

The framework is published openly on GitHub at https://github.com/hci-lab-um/heuristics-for-test-tool-design under a Creative Commons licence, making it freely available to practitioners worldwide.

**Key terms:** idea-t; Heuristics; Why? / Who? / Context?; Shape of heuristics; Iterative prototyping; ISO 25010; Quality attributes; TsST; Illusion of Usability; Personas

**Key references:** Nielsen and Molich [137]; Nielsen [138]; Kipling [139]; Checkland and Poulter [37]; Zachman [222]; ISO 25010 [11]; Evans et al. [42]

</details>

---

The following longer summary from Claude covers the reason for the idea-t framework, methods used when designing and building it, results of protoyping, and then the discussion, conclusion and next steps.

<details close><summary>Reason for the idea-t framework</summary>
  
### Reason for the Framework


The first two research studies revealed two things that had not previously been documented together. First, testers experience their tools as frustrating, sometimes frightening, and often inadequate — not because the tools are technically poor, but because they are designed with a superficial understanding of usability and a narrow picture of who testers are. Second, testers are an unusually heterogeneous community: with backgrounds ranging from IT to arts, medicine, philosophy, and boat building, they cannot be captured in a simple, fixed persona set.

These two findings created a problem: if you cannot build a standard set of user personas for testers, how do you help tool designers and purchasers think carefully enough about the people who will use their tools? The answer explored in this research was a **framework of heuristics** — structured questions that help people investigate their own context, rather than providing generic answers that may not apply.

This chapter answers **RQ1.3: How could HCI design heuristics inform test tool design?**

</details>

---

<details close><summary>Methods Used</summary>
  
### Methods

#### About Heuristics

Heuristics are rules of thumb that guide thinking without prescribing outcomes. They are already well-established in both software testing (where testers use heuristics to guide their testing decisions) and in HCI (where Nielsen's Ten Usability Heuristics [138] are widely used for evaluating interfaces). Using a format already familiar to practitioners increases the likelihood of adoption.

Before developing the *content* of the heuristics, work was done to understand the best *format*. A study of heuristics from UX practice, software testing, road signs, proverbs, advertising slogans, and everyday life produced a classification with two dimensions:

- **Format:** Textual (written words), Pictorial (images and symbols), or Conceptual (metaphors and acronyms)
- **Directiveness:** Asking (questions that provoke thought), Prompting (suggestions), or Telling (instructions)

A pilot study with five UX practitioners tested all nine combinations. The result was a clear preference for **textual, asking-style heuristics** — questions expressed in plain English. Pictorial heuristics raised accessibility concerns; conceptual heuristics raised cross-cultural inclusivity concerns (metaphors do not translate equally across languages and cultures). This classification — called the **"shape of heuristics"** model — was published as a position paper [42].

#### Developing the Content

Starting with over 150 candidate heuristic questions derived from the research data (Chapters 5 and 6), these were grouped and reduced through nine iterations of expert review and practitioner trials, involving 28 participants and resolving 208 issues. Expert reviewers were drawn from the testing, UX, and accessibility communities in Europe and North America. Participants represented a range of testing viewpoints — context-driven, agile, analytical, standards-based — to ensure the heuristics were robust across different worldviews.

The iterative development was informed by three existing frameworks that influenced the structure of the idea-t framework:

- **The 5 W's and H** (Who? Why? Where? What? When? How?) [139] — the classic questioning framework, attributed in part to Kipling's poem "Six Serving Men"
- **The Zachman Framework for Enterprise Architecture** [222] — a matrix of the 5W's and H applied to enterprise design, demonstrating the value of structured questions
- **Soft Systems CATWOE and LUMAS** (after Checkland [37]) — frameworks that place people at the centre of systems and acknowledge that change affects different people in different ways — as beneficiaries or as victims

Ethics approval ICT2024-00010 was obtained for the prototyping work.

</details>

---

<details close><summary>Results of Prototyping</summary>
  
### Results of Prototyping

The twelve heuristic questions produced are shown in Table 8.1 of the dissertation. They divide into three themes:

| Theme | Keyword | Heuristic |
|---|---|---|
| **Why?** | Why? | H01: Why is this tool needed? |
| **Who?** | Who? | H02: Who will use or be affected by this tool? |
| **Who?** | Experience? | H03: What previous experiences do people bring? |
| **Who?** | Communication? | H04: What communication needs or preferences do people have? |
| **Who?** | Learning goals? | H05: Do people want "tool mastery" or "task completion"? |
| **Who?** | Learning preferences? | H06: What learning preferences do people have? |
| **Context?** | Where? | H07: Where will the tool be used? |
| **Context?** | Workflows? | H08: What workflows is the tool part of? |
| **Context?** | Risks? | H09: What risks are associated with those workflows? |
| **Context?** | Autonomy? | H10: What autonomy of work styles is allowed? |
| **Context?** | When? | H11: When will the tool be used? |
| **Context?** | How long? | H12: How long will the tool be used? |

*Based on Table 8.1 in the dissertation*

For each heuristic, the framework provides:
- A **quick-start** prompt for fast use
- **Sub-questions** (including "else?" and "not?" variants)
- **Research evidence** and participant quotes from Chapters 5 and 6
- **Suggested activities** (e.g. stakeholder mapping, persona development, risk-storming, journey mapping)
- **ISO 25010 quality attribute links** — connecting each heuristic to the quality attributes most relevant to it, ordered by frequency of mention in the research data

The framework also includes navigation guidance, fast-path options for experienced users, and links to the research process and anonymised data.

</details>

---

<details close><summary>Discussion, Conclusions and Next Steps</summary>
  
### Discussion

The idea-t framework is specifically designed to address the three illusions of usability identified in Chapter 5:

- **Illusion 1** (usability = an attractive interface) is challenged by the full set of quality attribute links, which direct attention to deeper design decisions beyond the user interface.
- **Illusion 2** (usability = quality in use) is challenged by the explicit inclusion of technical quality attributes (maintainability, portability, performance, reliability) alongside usability attributes.
- **Illusion 3** (users don't change) is challenged by H05 (learning goals), H06 (learning preferences), and H12 (how long will the tool be used?) — all of which direct attention to how users grow, change, and evolve over time.

An early trial of using the framework — before the content was fully developed — involved using parts of the framework with a group of testing experts planning an annual event. This confirmed that an automated approach to generating tool requirements from input data would be too complex to build, and that a heuristic approach — involving human judgment guided by structured questions — was the right direction.

The format (textual, asking-style) was validated by practitioner response during both prototyping and the subsequent case studies. Practitioners used the heuristics flexibly — not in order, not completely — and tailored questions to their context, which is exactly the flexibility the framework was designed to support.


---

### Conclusions

- Heuristics are an appropriate and practically effective format for the idea-t framework, given the diversity of testing contexts and the impossibility of a fixed persona set.
- Textual, asking-style heuristics are preferred by practitioners over pictorial or telling-style alternatives.
- The twelve heuristics, organised around Why? / Who? / Context?, provide structured prompts that help tool designers and purchasers go beyond stereotypes and surface assumptions.
- The framework explicitly addresses the illusion of usability by connecting heuristics to the full range of quality attributes — not just usability — and by attending to users who grow and change over time.
- The idea-t framework is available openly on GitHub, and is designed to be used flexibly, in any order, with any subset of heuristics, tailored to context.

---

### Next Steps

The idea-t framework was taken into five formative industry case studies (Chapter 9) for evaluation and iterative refinement. Changes were made after every case study, moving from v1.01 to v1.06. The framework was then subjected to a retrospective analysis (Chapter 10) and a summative expert review (Chapter 11), before a final discussion and conclusions (Chapters 12 and 13).

Future work includes: developing the framework in alternative media formats (poster, book, PDF, video, playing cards); further developing the "shape of heuristics" model into a larger study [42]; and exploring AI-assisted use of the framework.


</details>

---

### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **idea-t** | Influencing the Design, Evaluation and Acquisition of Tools for Testing — the framework of heuristics developed as the main output of this research |
| **TsST** | Tools to Support Testing — any tool used to support any testing activity |
| **Heuristic** | A rule of thumb that aids problem-solving, providing answers that are often but not always correct, and which are therefore fast but fallible. In this context, question-based prompts to guide thinking |
| **Shape of heuristics** | The classification model developed in this research describing heuristics by format (textual, pictorial, conceptual) and directiveness (asking, prompting, telling) |
| **ISO 25010** | International standard for systems and software quality models, including quality in use and product quality attributes |
| **Quality in use** | The degree to which a product meets users' needs in a specific context — covering effectiveness, efficiency, satisfaction, freedom from risk, context coverage, and flexibility |
| **Illusion of usability** | The belief that usability equals an attractive interface, and/or that usability alone equals quality in use |
| **Persona** | A fictional character representing a group of users, used in design to guide decisions |
| **CATWOE** | Customers, Actors, Transformation, World view, Owners, Environment — a Soft Systems framework for understanding stakeholders in a change process (after Checkland [37]) |
| **LUMAS** | Learning, User, Methodology, Approach, Situation — a Soft Systems framework that places users at the centre of transformations (after Checkland [37]) |
| **5 W's and H** | Who? Why? Where? What? When? How? — the classic question framework, used as a structural basis for the idea-t framework |

---

### Key References

- [11] ISO 25010 — Systems and software quality models
- [37] Checkland and Poulter — Soft Systems Methodology (CATWOE and LUMAS)
- [42] Evans et al. — Shape of heuristics (published position paper)
- [109] Graham and Fewster — Testing tool design and automation
- [137] Nielsen and Molich — Heuristic evaluation of user interfaces
- [138] Nielsen — Ten Usability Heuristics
- [139] Kipling — "Six Serving Men" (5 W's and H)
- [203] Coplien and Harrison — Heuristics and patterns in software design
- [217] Petrie and Power — Heuristics evaluation methodology
- [218] Quinones and Rusu — Methodology for usability heuristics
- [222] Zachman — Zachman Framework for Enterprise Architecture

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
