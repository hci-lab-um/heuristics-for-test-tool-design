# Examining the Research: What Did I Learn?

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

The final two chapters of the dissertation are a discussion of the research, and a set of conclusions; in brief, what ISabel learnt from the research, new findings, and the implications of those findings.

Clause produced a 500-word precis:

---

<details close><summary>500-word Precis</summary>

## 500-Word Précis

### Examining the Research: What Did I Learn?

The final two chapters of the dissertation draw together all the threads of the research, evaluate the findings critically, and reflect on what the work contributes — to academic knowledge and to industry practice.

**Chapter 12** discusses and evaluates the results across all three research questions. The discussion of RQ1.1 confirms existing industry knowledge about tool impediments, while adding two genuinely new insights: the emotional dimension of testers' tool experiences (their **lived experience, LX**), and the concept of the **illusion of usability**. The discussion of RQ1.2 confirms that testers are a non-stereotypical and heterogeneous group, with implications that extend beyond tool design into recruitment, retention, and careers. The discussion of RQ1.3 evaluates the idea-t framework, first by applying it to itself as a self-test, and then by comparing it systematically with other frameworks: Nielsen's Ten Heuristics, the 5 W's and H, the Zachman Framework, Soft Systems CATWOE and LUMAS, the Automation in Testing (AiT) framework, and testing discussion card sets. Each comparison clarifies what idea-t adds, where it overlaps, and what future work would be beneficial.

**Chapter 13** states five formal contributions to knowledge: the idea-t framework (major), and four minor contributions — the understanding of testers as non-stereotypical, the understanding of testers' lived experience, the illusion of usability concept, and the shape of heuristics model. Limitations are acknowledged honestly, especially the geographic gaps in participation (no African participants; limited South American representation). Six published papers from the research are listed. The chapter ends with reflections on eight years of doctoral study, noting that the research consistently challenged — and revised — the researcher's own assumptions.

A particularly noteworthy finding was that the idea-t framework, when applied to itself as a tool, revealed new insights and gaps — confirming both that the framework works, and that continued improvement is needed.

**Key terms:** idea-t; Illusion of Usability; LX (Lived Experience); Heuristics; Contributions to knowledge; Limitations; Reflective practice; TsST

**Key references:** Evans et al. [38, 39, 40, 41, 42, 43]; Nielsen [138]; Checkland and Poulter [37]; McChesney et al. [175]; Wiklund et al. [32]

</details>

---

## 1000-Word Summary

With the help of Claude AI, a 1000-word summary was produced, with the parts: What did I learn? 

 
### Examining the Research: What Did I Learn?

---

<details close><summary>Key Findings</summary>
 
### Summary of Key Findings

The research set out to answer one central question — *"How can HCI techniques help with the design of test tools?"* — through three sub-questions. The final chapters assess the answers.

**Finding 1: Testers' lived experiences are significantly affected by their tools (RQ1.1)**

The research confirmed that tool problems in testing are well-known — organisational impediments, technical challenges, and usability problems have been described in the grey literature for decades. What was new was:

- The **emotional dimension**: around 30% of participants expressed emotion in their survey responses — fear, frustration, anger, pride. One participant considered leaving their job because of tool frustrations. These responses were found across all types of questions, including apparently factual ones. The presence of this emotional content — in an anonymous written survey, not just in interviews — indicates that the effect of tools on testers' **lived experience (LX)** is real and significant. It extends beyond work productivity into wellbeing, motivation, and professional identity.

- The **illusion of usability**: three forms were identified. First, treating usability as an attractive interface, when deeper workflow support and technical quality attributes matter more in extended use. Second, treating usability as the whole of quality in use, when technical attributes (maintainability, portability, performance, compatibility) are equally important to testers. Third, designing for a static, unchanging user, when real testers grow, change roles, and develop new needs over time. The illusion explains why tools that pass initial evaluation so frequently fail in extended use — they are designed to impress buyers, not to support users.

A quote from one participant captures the first illusion precisely: "…looks cool … but… took time to set up, lack info online, user-unfriendly UI in configuration. Not all configured things worked."

**Finding 2: Testers are a non-stereotypical and heterogeneous group (RQ1.2)**

With only 6% of tester participants matching the O*NET IT worker stereotype, the finding that testers are unusually diverse was confirmed beyond expectation. The practical implications are significant: tools designed around a narrow, stereotypical user will serve the minority and frustrate the majority. Beyond tool design, this finding has implications for recruitment, retention, and career paths in testing. The finding that senior managers (directors and heads of department) in the sample showed a higher proportion with limited development and UX experience raises questions about decision-making at the organisational level when tools are acquired — though the sample was too small to generalise from.

**Finding 3: HCI heuristics can meaningfully inform test tool design (RQ1.3)**

The idea-t framework delivered practical, real-world benefits across five industry case studies. One organisation saved approximately €20,000 in avoided licence fees. Another discovered and began to resolve an inter-departmental communication gap. A consultancy gained new strategic insights about tool lifecycle. The retrospective analysis indicated that approximately 40% of real customer issues could have been positively influenced by earlier use of the framework. The summative expert review found nearly 70% of coded comments were positive. This combination of evidence — from different types of study, with different participants, across different contexts — provides a robust basis for confidence in the framework's practical value.

</details>

---

<details close><summary>Discussion: Using idea-t on itself and comparing idea-t to other frameworks</summary>

### Discussion

**Applying idea-t to itself**

One of the most illuminating sections of Chapter 12 is the application of the idea-t framework to itself, treating the framework as a tool. Working through all twelve heuristics:

- **H01 (Why?)** confirms that the framework is needed: tool design decisions are frequently made without sufficient understanding of users and context, and the case studies, retrospective, and expert reviews demonstrate genuine benefits.
- **H02–H06 (Who?)** reveals that the framework's users are diverse — tool designers, purchasers, consultants, managers, trainers — with very different levels of UX knowledge and very different time constraints. This reinforces the need for fast-path entry points alongside the full framework.
- **H07–H12 (Context?)** highlights that the framework needs to work across GitHub and beyond, in offices and at home, over short meetings and sustained strategy sessions. H12 (How long?) was particularly revealing: the framework itself has a lifecycle — it needs to be maintained, updated to new ISO standards, and potentially overhauled as technology changes.

The self-test confirmed both that the framework works — it generates genuine insights even when applied to itself — and that improvement in navigation, media, and structure is needed.

**Comparing idea-t to other frameworks**

The discussion compares idea-t systematically to six other frameworks or sets of heuristics, with the key conclusions shown below:

| Framework | Relationship to idea-t |
|---|---|
| Nielsen's Ten Usability Heuristics [138] | Complementary: idea-t is for design and acquisition decisions; Nielsen's is for interface evaluation |
| 5 W's and H [139] | idea-t extends and deepens the classic questions, particularly Who? and adds How long? |
| Zachman Framework [222] | Shared matrix structure; idea-t brings Who? and Why? to the front, with an evidence base |
| Soft Systems CATWOE and LUMAS [37] | Informed idea-t's people-centred approach; idea-t makes explicit the roles of beneficiaries and victims |
| Automation in Testing (AiT) | Similar philosophy (people over tools); idea-t has wider scope (all TsST, not just automation) and an explicit evidence base |
| Testing discussion card sets | Models for future media formats for idea-t |

The comparison with AiT is particularly noteworthy: one expert reviewer's initial reaction was that idea-t was not new. Once they examined the detailed content, they acknowledged the wider scope and different evidence base — a useful lesson in the importance of supporting frameworks with accessible evidence and clear navigation.

</details>

---

<details close><summary>Conclusions</summary>
  
### Conclusions

Five formal contributions to knowledge are claimed:

1. **The idea-t framework** (major contribution) — twelve evidence-based heuristics, supported by guidelines, activities, and quality attribute links, published openly on GitHub under a Creative Commons licence
2. **Testers as a non-stereotypical group** (minor) — published in two papers [41, 43]
3. **Testers' lived experience** (minor) — published in two papers [38, 39]
4. **The illusion of usability** (minor) — published in one paper [40]
5. **The shape of heuristics model** (minor) — published in one position paper [42]

Potential challenges to the contributions are addressed honestly: the focus on testers as a specific community means generalisation to other groups requires further research; the geographic gap (no African participants) is a known limitation; and the current GitHub repository (v1.7) has structural and navigational weaknesses that are being addressed in v2.0.

---

### Next Steps

Two streams of immediate future work are identified:

1. **Refining the idea-t framework** — resolving the outstanding structural and navigation improvement suggestions from the expert reviews, developing alternative media (poster, book, PDF, video), and improving fast-path materials for different user types. This work is in progress.

2. **Distributing idea-t** — presentations at industry conferences, online community engagement, and distribution of the framework poster and other materials. This is also in progress, with the research already being referenced in industry discussions about AI, testing, and tool design.

Longer-term future work (detailed in Appendix N) includes: extending the research to under-represented geographic regions; applying the methods to other tool domains; investigating AI in testing tools; and developing training materials for the framework.

The researcher's reflective conclusion — after eight years of doctoral study — is that the results were consistently surprising. The diversity of testers, the emotional depth of their tool experiences, and the persistence of the illusion of usability were all things the research uncovered, not things it confirmed. This, in itself, is a powerful argument for the value of rigorous, evidence-based research in industry practice.

</details>

---

### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **idea-t** | Influencing the Design, Evaluation and Acquisition of Tools for Testing |
| **TsST** | Tools to Support Testing |
| **LX** | Lived Experience — the effect of technology use extending beyond immediate tasks into wellbeing and daily life |
| **TX** | Tester Experience — the specific lived experience of software testers |
| **Illusion of Usability** | The belief that usability equals an attractive interface, and/or that usability alone equals quality in use |
| **Heuristic** | A rule of thumb that aids problem-solving, providing fast but fallible guidance |
| **Shape of heuristics** | Classification of heuristics by format (textual, pictorial, conceptual) and directiveness (asking, prompting, telling) |
| **AiT** | Automation in Testing — a people-centred framework for test automation design and training |
| **O*NET** | US Occupational Information Network — used to compare tester characteristics against IT worker profiles |
| **CATWOE** | Customers, Actors, Transformation, World view, Owners, Environment — a Soft Systems stakeholder analysis framework |
| **LUMAS** | Learning, User, Methodology, Approach, Situation — a Soft Systems people-centred framework |

---

### Key References

- [11] ISO 25010 — Systems and software quality models
- [25] ISO 25019 — Updated quality standard (2024)
- [37] Checkland and Poulter — Soft Systems Methodology
- [38] Evans et al. — Stuck in Limbo with Magical Solutions (HUCAPP 2020)
- [39] Evans et al. — Scared, Frustrated and Quietly Proud (ECCE 2021)
- [40] Evans et al. — Test tools: an Illusion of Usability (TAIC PART 2020)
- [41] Evans et al. — Breaking Tester Stereotypes (BCS HCI 2024)
- [42] Evans et al. — How Can Heuristics Be Communicated? (CHIRA 2024)
- [43] Evans et al. — The software testing community and IT stereotypes (IWC 2025)
- [138] Nielsen — Ten Usability Heuristics
- [139] Kipling — "Six Serving Men" (5 W's and H)
- [175] McChesney et al. — IT worker stereotypes and diversity
- [222] Zachman — Zachman Framework for Enterprise Architecture

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
