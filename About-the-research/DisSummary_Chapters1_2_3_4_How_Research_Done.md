# How Was the Research Done?

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

This is a summary of the first four chapters of the dissertation, providing an overview of the reason for reasearch, the review of related literature, the theoretical framework within which the research was done, and the methodology used for the research.

---

## 500-Word Précis

<details close><summary>500 word precis</summary>

### How Was the Research Done?

Software testing is vital to the quality and safety of almost every piece of software in daily use. It is supported by tools — and those tools are too often bought and not properly used (**shelfware**), or used but failing to deliver. Despite this longstanding problem, almost no prior research had applied Human-Computer Interaction (HCI) techniques to the tools used by testers.

This dissertation addresses that gap. The central research question is: **"How can HCI techniques help with the design of test tools?"** This breaks into three sub-questions: What are testers' experiences with test tools? What are the characteristics of testers? And how can HCI heuristics inform tool design?

The **literature review** (Chapter 2) surveys the field of software testing — with its multiple competing viewpoints and decades of evolution — and the field of HCI, establishing that testers and their tools have been almost entirely absent from HCI research. The review identifies a clear gap: usability has been shown to be a barrier to test automation, but no systematic study had investigated the full range of testers' tool experiences, or applied HCI methods to the design of those tools.

The **theoretical framework** (Chapter 3) is built around three sources: HCI (to understand people and their goals), soft systems thinking (to place people at the centre of complex sociotechnical systems), and design thinking (to support iterative, exploratory problem-solving). Quality is examined through Garvin's five viewpoints, and the levels of automation model is used to explore the shifting relationship between testers and their tools.

The **methodology** (Chapter 4) is **mixed methods** and grounded in **pragmatism**, drawing on interpretivism and critical realism. Data was collected through interviews, workshops, surveys, expert reviews, case studies, and retrospective analysis, with nearly 300 participants across eight years. The "of me" nature of the research — the researcher is herself a member of the testing community — is acknowledged and mitigated through open questioning, independent recoding, and member checking. All studies were conducted under University of Malta ethics approval.

**Key terms:** TsST (Tools to Support Testing); HCI (Human-Computer Interaction); Shelfware; Mixed methods; Pragmatism; Quality in use; Levels of automation; Soft systems thinking; Design thinking

**Key references:** Saunders [2]; Wiklund et al. [32]; Checkland and Poulter [37]; Garvin [12]; Cummings [169]

</details>
---

## 1000-Word Summary


This 1000 word summary provides more detail abour the purpose and target of the research, the research domain, why the research was needed, the theoretical framework, and the methodology.

---

<details close><summary>Purpose and Target</summary>

### Purpose and Target of the Research

Software testing is a critical activity in software delivery. Every piece of software that affects daily life — banking apps, hospital systems, aircraft controls, retail websites — needs to be tested. Testing is supported by tools: test management systems, defect trackers, automation frameworks, performance testing platforms, and dozens of other specialist applications. These **Tools to Support Testing (TsST)** are intended to make testing more efficient and more effective.

But a persistent and expensive problem has been recognised in the industry for decades. Tools are acquired but not properly used — a phenomenon known as **shelfware**. The cost of shelfware is not just financial; it represents lost opportunity, wasted time, and in some cases a direct degradation of software quality when testing is less effective because its tools have failed. Industry authors and researchers including Graham and Fewster [109], Wiklund et al. [32], and Kaner [33] have documented this problem, and successive World Quality Reports [22, 23, 24] have confirmed it.

The research addresses this problem through one central research question: **"How can HCI (Human-Computer Interaction) techniques help with the design of test tools?"** This breaks into three sub-questions:

- **RQ1.1:** What are testers' experiences with test tools?
- **RQ1.2:** What are the characteristics of testers using test tools?
- **RQ1.3:** How could HCI design heuristics inform test tool design?

The research places **people** at the centre. Testers are not just operators of technology — they are skilled, diverse, and human. Understanding who they are, what they experience, and what they need is the essential first step towards tools that actually work for them.

</details>

---

<details close><summary>Understanding the research domain</summary>

### Understanding the Research Domain

**Software testing** has evolved significantly since the 1950s, developing through several distinct viewpoints or "schools" [17, 18]: analytical (testing as engineering rigour), standard (testing governed by certifications and processes), quality (testing as a quality gatekeeping activity), agile (testing embedded throughout development), and context-driven (testing as adaptive, cognitive, people-centred work). The dissertation does not privilege one viewpoint over another — it acknowledges all of them as valid in different contexts, because the tools that support testing need to work across all of them.

The **literature review** (Chapter 2) surveys the history of test tools, from the relatively small number of tools available in the 1980s to the many hundreds available today. It introduces key concepts including:

- **Shelfware:** Tools acquired but not properly used [33, 34, 35]
- **Usability as an impediment:** Wiklund et al. [32] identified usability as the most frequently cited barrier to test automation, calling for practical, packaged solutions for industry
- **Developer tool usability:** Work by Murphy-Hill's team [15, 142] found that developers ignore warnings from static analysis tools they cannot understand — pointing to a broader pattern of tool usability failure in software engineering
- **HCI concepts:** Usability, quality in use (ISO 25010 [11]), user experience (UX), lived experience (LX), and personas — all of which become central to the research

A systematic search of academic databases found almost no prior work applying HCI methods specifically to the tools used by testers. This absence — the **research gap** — motivated all three research questions.

</details>

---

<details close><summary>Why the research was needed</summary>

### Why the Research Was Needed

Two reasons, complementary to each other, drive the need for this research.

First, **the evidence of a problem.** Despite decades of awareness, shelfware persists. Successive World Quality Reports confirm that tool adoption remains challenging. The usability of test tools is a "major factor" affecting testing efficiency [146]. Yet the people doing testing and their experiences with tools had never been systematically studied using HCI methods.

Second, **the absence of solutions.** Wiklund et al. [32] called for practical, industry-useful responses to the usability problem. Developer tool research (Murphy-Hill's team [15, 142]) showed what the problem looks like in an adjacent community, but nobody had investigated it specifically in testing. No prior research had asked testers, in their own words, about their tool experiences; no prior research had characterised testers as a user group using HCI methods; and no prior research had developed HCI-based heuristics for test tool design.

The research fills this gap in three steps, matching the three sub-questions. The approach is described in the methodology.

</details>

---

<details close><summary>Theoretical Framework</summary>

### Theoretical Framework

The theoretical framework (Chapter 3) is built around three interconnected bodies of knowledge:

**1. HCI (Human-Computer Interaction)**
HCI provides the methods and concepts needed to understand people and their interactions with technology. Key concepts used throughout the research include:
- **Usability** — ease of use, particularly for novice and intermediate users
- **Quality in use** (ISO 25010 [11]) — the degree to which a system meets users' needs in their specific context, covering effectiveness, efficiency, satisfaction, freedom from risk, context coverage, and flexibility
- **User experience (UX)** — the full range of experiences a person has when using a product
- **Lived experience (LX)** — the effect of technology use extending into daily life and wellbeing, beyond the immediate task (after Porter [8])
- **Personas** — fictional user profiles used in design to represent groups of users

**2. Soft systems thinking** (after Checkland [37])
Soft systems methodology places **people** at the centre of systems, acknowledging that different people have different worldviews, and that change will have both beneficiaries and victims. Key frameworks used include CATWOE (Customers, Actors, Transformation, World view, Owners, Environment) and LUMAS (Learning, User, Methodology, Approach, Situation). Both frameworks informed the structure and content of the idea-t framework, particularly the emphasis on Who? and Why? as the starting questions.

**3. Design thinking**
Design thinking supports iterative, exploratory problem-solving — building prototypes, testing them, learning, and refining. Unlike engineering thinking ("are we building it right?") or research thinking ("does this confirm our hypothesis?"), design thinking asks "are we building the right thing?" This approach underpinned the development of the idea-t framework through nine prototype versions and five formative case studies.

The theoretical framework also uses **Garvin's five quality viewpoints** [12] — manufacturing-based, product-based, user-based, value-based, and transcendent — to show that "quality" means different things to different stakeholders in the tool design and acquisition chain. This multiplicity of viewpoints is one reason why the illusion of usability persists: designers, purchasers, and users all have different quality expectations, and none of them is wrong.

The relationship between people and automation is explored using Cummings' model [169] of ten levels of automation, from full human control to full computer autonomy. As tools become more automated, the tester's role shifts — and with it the risks of **automation bias** (uncritically trusting automated results) and deskilling. These ideas directly inform several of the idea-t heuristics, particularly H10 (Autonomy) and H09 (Risks).

The relationship between the System Under Test (SUT) and the Test System (TS) — the environment within which testing takes place — adds another layer of complexity: both systems need to be maintained, both change constantly, and any tool that supports testing is part of that changing, recursive whole.

</details>

---

<details close><summary>Methodology</summary>

### Methodology

**Philosophical position:** The research is grounded in **pragmatism** — the belief that practical know-how is valid knowledge, and that research should lead to improvements in practice. It draws additionally on **interpretivism** (participants' stories and experiences are genuine knowledge) and **critical realism** (reality is complex, layered, and context-dependent). Together, these positions justify the mixed-methods approach and the use of both qualitative and quantitative data.

The reasoning approach is **abductive** — exploring data openly, without a fixed hypothesis, allowing unexpected patterns to emerge. Both the illusion of usability and the emotional depth of testers' tool experiences were unexpected findings, discovered through open, non-hypothesis data collection.

**Research design:** The methodological choices are organised using Saunders' Onion Model [2] (Figure 4.1 in the dissertation), which shows how philosophical stance, approach, strategy, and methods nest inside each other. The research uses a **mixed methods** strategy, combining qualitative methods (interviews, workshops, open surveys, case study diaries, expert reviews) with quantitative methods (frequency analysis, sentiment coding, demographic comparison).

**Methods and participants:**

| Research Question | Methods Used | Participants |
|---|---|---|
| RQ1.1 — Experiences | Conversations, expert interviews, workshops, surveys | 150 |
| RQ1.2 — Characteristics | Anonymous online survey | 78 |
| RQ1.3 — Heuristics | Modelling, expert review, practitioner trials, case studies, retrospective analysis, summative review | 48 (across all RQ1.3 studies) |
| **Total** | | **~245–300** |

*Based on Table 4.4 in the dissertation*

**Ethics:** All studies were conducted under University of Malta Faculty Research Ethics Committee (FREC) approval (approval numbers cited in each chapter). All participants were anonymised except the seven summative expert reviewers, who gave informed consent to be named in the dissertation. Commercially sensitive data was protected throughout; where data could not be sufficiently anonymised, datasets were not shared, but research instruments were made available on OSF (Open Science Framework).

**Validity and bias:** The "of me" nature of the research — the researcher is herself a testing practitioner with nearly 40 years of industry experience — was mitigated through: open, non-leading questions; independent recoding of data by supervisors; member checking of case study reports; deliberate recruitment of participants from diverse and sometimes opposing testing viewpoints; and comparison of sample demographics with five industry reports and conference profiles.

Sample sizes are appropriate for qualitative work and were validated against industry demographic data. Where group effects were observed in workshops (some participants feeling inhibited from expressing honest opinions), subsequent data collection was designed around anonymous surveys and one-to-one interviews.

</details>

---

<details><summary>References, Glossary and Abbreviations</summary>

### Key References

- [2] Saunders — Research Methods for Business Students (Onion Model)
- [7] Baltes and Ralph — Sampling in software engineering research
- [8] Porter — Lived experience and design
- [11] ISO 25010 — Systems and software quality models
- [12] Garvin — Five quality viewpoints
- [22, 23, 24] Capgemini — World Quality Reports
- [31] Bach and Bolton — Context-driven approach to automation in testing
- [32] Wiklund et al. — Usability as an impediment to test automation
- [33] Kaner — Shelfware
- [37] Checkland and Poulter — Soft Systems Methodology
- [109] Graham and Fewster — Software Test Automation
- [142] Johnson et al. — Developers' experiences with static analysis tools
- [169] Cummings — Levels of automation
- [176] Singer and Vinson — Ethical dilemmas in empirical software engineering research

---

### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **TsST** | Tools to Support Testing — any tool used to support any testing activity |
| **HCI** | Human-Computer Interaction — the academic and professional discipline studying how people interact with technology |
| **Shelfware** | Software tools acquired but not properly used |
| **LX** | Lived Experience — the effect of technology use extending beyond immediate tasks into daily life and wellbeing |
| **UX** | User Experience — encompassing all aspects of end-user interaction with a product |
| **Quality in use** | The degree to which a product meets users' needs in a specific context (ISO 25010 [11]) |
| **Pragmatism** | A philosophical position holding that practical know-how is a valid form of knowledge, and that research should lead to improvements in practice |
| **Interpretivism** | A philosophical position holding that people's stories, experiences, and interpretations are valid knowledge |
| **Critical realism** | A philosophical position holding that reality is structured, layered, and context-dependent |
| **Abductive reasoning** | A reasoning approach that explores data openly without a fixed hypothesis, allowing unexpected patterns to emerge |
| **Mixed methods** | A research approach combining qualitative and quantitative methods |
| **"Of me" research** | Research in which the researcher is themselves a member of the community being studied |
| **Member checking** | Sharing research analysis with participants to verify accuracy — a standard validity step in qualitative research |
| **FREC** | Faculty Research Ethics Committee — the University of Malta body that approved all studies in this research |
| **SUT** | System Under Test — the software being tested |
| **TS** | Test System — the environment and toolset within which testing takes place |
| **Automation bias** | The tendency to uncritically trust the results produced by automated systems |
| **CATWOE** | Customers, Actors, Transformation, World view, Owners, Environment — Soft Systems stakeholder framework |
| **LUMAS** | Learning, User, Methodology, Approach, Situation — Soft Systems people-centred framework |
| **OSF** | Open Science Framework — an online platform for sharing research data and instruments |


</details>

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
