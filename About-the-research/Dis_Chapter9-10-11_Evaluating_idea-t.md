# Evaluating and Refining the idea-t Framework

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

---

Claude produced this 500-word summary of chapters 9, 10 and 11 of the dissertation:

Once the idea-t framework had been developed through iterative prototyping, it needed to be tested in real industry settings and assessed by independent experts. Chapters 9, 10 and 11 describe three complementary evaluations.


<details close><summary>500-word precis</summary>

**Chapter 9: Five formative case studies** tested the idea-t framework across four organisations and five different usage contexts. Contexts ranged from evaluating a commercial vendor tool add-on, to reviewing in-house automation suites, to designing new features for an existing commercial tool, to planning a consultancy engagement, to setting an enterprise tooling strategy. Eight participants took part, all working at SFIA Level 5 or above.

Results were consistently positive. Key outcomes included: a team discovering that their real problem was an inter-departmental communication gap rather than the tool — saving approximately €20,000 in avoided licence fees; confirmation that the framework adds value at all stages of a tool's lifecycle, from new suites to mature suites; and one participant describing a single heuristic (H12 — How long?) as an "OMG" moment, opening entirely new thinking about tool lifecycle and decommissioning. The framework was improved after each case study, moving from v1.01 to v1.06, with 60 issues raised and resolved.

**Chapter 10: A retrospective analysis** asked whether the idea-t framework could have prevented real customer problems if applied at the design stage. Working with the same tool vendor organisation from Case Study 3, a sample of 100 customer issues — improvement requests, support queries, and user questions — was analysed against the heuristics. The finding was that approximately **40% of issues had at least one applicable heuristic** that could have positively influenced design decisions. The most frequently applicable heuristics were H08 (Workflows), H04 (Communication preferences), and H06 (Learning preferences).

**Chapter 11: A summative expert review** gathered assessments from seven experts drawn from testing, test tool design and building, tool acquisition, HCI and UX, heuristics design, and accessibility. Overall sentiment was strongly positive: nearly **70% of coded comments were positive**. Reviewers valued the evidence base, the non-prescriptive format, and the practical usefulness of the heuristics. Improvement suggestions focused mainly on the structure and navigation of the GitHub repository, and on providing the framework in additional formats (poster, book, PDF, video).

Together, these three evaluations confirm that the idea-t framework is understandable, useful, and flexible across a wide range of industry contexts.

**Key terms:** TsST; idea-t; Formative evaluation; Retrospective analysis; Summative expert review; Heuristics; Quality in use; Shelfware; SFIA

**Key references:** ISO 25010 [11]; Nielsen [138]; Petrie and Power [217]; Quinones and Rusu [218]

</details>

---

## 1000-Word Summary

This 1000 word summary provides more detail about the stages of evaluation through case studies, a retrospective analysis of customer issues for one commercial tool, and expert evaluations.  It is divided into the reason for the studies, the methods used, a summary of the findings, 


---

<details close><summary>Reason for the studies</summary>

### Reason for the Studies

The idea-t framework was developed from research data and refined through prototyping. But research data and expert prototyping are not the same as real-world use. Three further evaluations were needed: formative case studies to test the framework in industry settings and refine it iteratively; a retrospective analysis to test whether it could have predicted and prevented real customer problems; and a summative expert review to assess its overall quality, usefulness, and generalisability.

Together, these three evaluations answer the practical question that research must always ask: does it work?

</details>

---

<details close><summary>Methods</summary>
  
### Methods

#### Formative Case Studies (Chapter 9)

Five case studies were conducted across four organisations, each with a different purpose and tool context. All followed the same method: an introductory planning meeting, use of the idea-t framework by the participant(s) with diary-based data collection (Appendix J), analysis, a write-up, and member-checking with the lead participant.

| Case Study | Organisation Type | Tool Type | Scope |
|---|---|---|---|
| CS1 | Large multi-national, entertainment/leisure | OS and COM | Vendor tool evaluation by a potential customer |
| CS2 | Same organisation as CS1 | IH (in-house) | Review of three in-house automation suites |
| CS3 | Small tool vendor, Netherlands | COM (SaaS) | Design review of two new features |
| CS4 | Scandinavian consultancy | COM | Planning a customer tool evaluation |
| CS5 | Australasian consultancy | Mixed (COM, IH, OS) | Enterprise tooling strategy review (~5,000 engineers) |

*Based on Table 9.3 in the dissertation*

Eight participants took part across the five case studies, all at SFIA Level 5 or above. Ethics approval ICT-2024-00014 was obtained. All organisations and participants were anonymised using codes (O1–O4, P1–P8, V1–V2, T1–T12).

#### Retrospective Analysis (Chapter 10)

The retrospective analysis took place with the same tool vendor organisation as CS3. A sample of 100 customer issues over 18 months was assessed by the lead participant for: (a) importance (high, medium, low) and (b) the applicability of each heuristic — whether earlier use of the idea-t framework could have prevented or mitigated the issue.

#### Summative Expert Review (Chapter 11)

Seven expert reviewers were selected from a long-list of over 30 candidates. Selection criteria were: SFIA Level 6 or 7; international reputation; expertise across different areas (testing, HCI/UX, test tooling, heuristics design, accessibility). Reviewers were given tailored review briefs and spent approximately one hour with the framework materials, followed by a 30-minute discussion with the researcher. Comments were coded using Atlas-ti for sentiment and grounded theory analysis.

</details>

---

<details close><summary>Summary of the studies</summary>
  
### Summary of the First Five Case Studies Targets

**CS1** used heuristics H01 (Why?) and H02 (Who?) to reveal an inter-departmental communication gap between engineering and UX teams, where accessibility issues found by the tool were never communicated back to the UX department. The team decided not to purchase the proposed vendor tool add-on — saving approximately €20,000 in licence fees — and instead improved the communication process. H07 (Where?) and H08 (Workflows?) also drove useful insights about process gaps.

**CS2** reviewed three in-house automation suites — mature, new, and developing. Key finding: the framework's usefulness scales with the maturity and complexity of the tool. For a mature suite, the discussion was fast and confirmatory. For a new suite, almost all heuristics were relevant: "For this evaluation, almost all of the heuristics were very useful, especially since this tool is very new" [P1]. The case study also surfaced onboarding as a new usage scenario for the framework.

**CS3** worked with a small tool vendor to review two new features. The team — who already had strong UX expertise — discovered new insights particularly around H01 (the difference between what customers requested and what end users actually needed) and H12 (the lifecycle of the tool and its decommissioning). The team planned to build a tailored checklist from the heuristics for their internal wiki.

**CS4** revealed a limitation: the framework requires engagement and trust-building. Without a willing customer and appropriate context for structured discussion, the framework cannot be applied. This highlighted the need for clear introductory materials and for a relationship of trust between consultant and client.

**CS5** used the framework to review a tooling strategy for an enterprise with around 5,000 engineering staff. H12 (How long?) produced an "OMG" moment for the participant — opening thinking about tool lifecycle, maintenance costs, and decommissioning plans that had not previously been considered at a strategic level. The participant used mindmaps to work through the heuristics (Figures J.12–J.17 in the dissertation), showing a flexible and creative way of engaging with the framework.

</details>

---

<details close><summary>Who took part - the roles represented</summary>
  
### Who Took Part

| Study | N | Roles |
|---|---|---|
| Formative case studies | 8 participants across 4 organisations | Test domain architect, senior consultant, tool vendor director, team leads, testers |
| Retrospective analysis | 1 participant | Tool vendor representative, SFIA Level 6 |
| Summative expert review | 7 expert reviewers | Industry and academic; testing, HCI/UX, tool design and building, tool acquisition, heuristics, accessibility |

Expert reviewer expertise areas (anonymised as ER1–ER7):
- **ER1:** Industry practitioner and teacher; expertise in test tool design and building
- **ER2:** Industry practitioner; expertise in tool acquisition and heuristics design
- **ER3:** Industry practitioner and teacher; expertise in tool acquisition
- **ER4:** Academic; expertise in HCI, assistive technology, and heuristics
- **ER5:** Industry practitioner and teacher; expertise in tool design, building, and automation
- **ER6:** Senior industry manager; expertise in tool acquisition
- **ER7:** Industry practitioner and teacher; expertise in automation and test tooling

</details>

---

<details close><summary>Results</summary>
  
### Results

**Formative case studies:** All five produced positive outcomes. Key quantitative summary:

| Metric | Finding |
|---|---|
| Framework versions | v1.01 to v1.06 across the case studies |
| Issues raised and resolved | 60 |
| Benefits reported | Saved money, improved communication, new strategic insights, new usage scenarios identified |

*[Note: Table 9.9 in the dissertation provides a detailed breakdown of changes made after each case study — this table would be valuable to reproduce in a full publication.]*

Heuristic H12 (How long?) and H01 (Why?) were consistently among the most valuable. Heuristics H05 and H06 (learning goals and preferences) were sometimes not used — particularly where the tool's UX was perceived as high — which may reflect the persistence of the illusion of usability rather than genuine inapplicability.

**Retrospective analysis:** Of 100 customer issues sampled:

| Issue Importance | % with Applicable Heuristic |
|---|---|
| High (2 issues) | Both had highly applicable heuristics |
| Medium (24 issues) | ~67% had medium or high applicability |
| Low (74 issues) | ~32% had medium or high applicability |
| **Total** | **~40% had at least one applicable heuristic** |

Most frequently applicable heuristics: H08 (Workflows), H04 (Communication preferences), H06 (Learning preferences).

**Summative expert review:**

| Sentiment | % of Coded Comments |
|---|---|
| Positive | ~69% |
| Unsure | ~25% |
| Negative | ~6% |

Negative comments were concentrated in one area: the structure and navigation of the GitHub repository. Positive comments focused on: the evidence base underlying the heuristics; the non-prescriptive, question-based format; and immediate practical usefulness. The heuristics that challenged existing assumptions (H05 and H12) were particularly valued.

</details>

---

<details close><summary>Discussion, Conclusions and Next Steps</summary>
  
### Discussion

The formative case studies confirm that the idea-t framework delivers real and varied benefits across diverse contexts. The benefit in CS1 — avoiding an unnecessary tool purchase — is a concrete, quantifiable example. The benefit in CS5 — strategic thinking about tool lifecycle — is less tangible but potentially more significant.

The retrospective analysis provides indicative evidence that earlier use of the idea-t framework at the design stage could reduce post-release customer issues. The 40% figure is not a causal claim — the participant noted that some issues were outside the scope of what the heuristics could address — but it is a practically significant finding.

The expert review results confirm strong overall confidence in the framework, while also clearly identifying the priority areas for improvement: structure and navigation of the GitHub repository, and the development of alternative media formats. The observation that both the most technically sophisticated reviewers (who found GitHub natural and familiar) and those with different backgrounds (who preferred other media) had different experiences of accessing the framework is itself an example of H04 (Communication preferences) in action.

---

### Conclusions

- The idea-t framework delivers real, practical benefits in diverse industry settings — from strategic tooling decisions to detailed design reviews.
- Approximately 40% of real customer issues from a commercial tool vendor could have been positively influenced by earlier use of the idea-t framework.
- Nearly 70% of expert review comments were positive, confirming the framework's quality and practical usefulness.
- The key area for improvement is accessibility and navigation — particularly for users who are unfamiliar with GitHub or who prefer non-textual formats.
- The framework's flexibility is a strength: it is used differently by different people, in different orders, for different purposes, and at different stages of a tool's lifecycle.

---

### Next Steps

Immediate improvements to the GitHub repository's structure, navigation, and fast-path materials have been made as part of the dissertation submission. Future work includes:

- Developing the framework in alternative media formats (poster, book, PDF, video, playing cards, training materials)
- Providing tailored routes through the framework for different user types (novice, experienced, tool builder, tool purchaser)
- Investigating AI-assisted use of the framework, as suggested by two expert reviewers
- Replicating the quality attribute ordering study at a later date, to see whether the priority order changes as the ISO 25019 standard replaces ISO 25010

</details>

---

### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **idea-t** | Influencing the Design, Evaluation and Acquisition of Tools for Testing |
| **TsST** | Tools to Support Testing |
| **Formative evaluation** | Evaluation conducted during the development of a tool or framework, with the purpose of improving it |
| **Summative evaluation** | Evaluation conducted after development is complete, with the purpose of assessing overall quality and effectiveness |
| **Retrospective analysis** | An evaluation looking back at past data to assess whether an intervention could have made a difference |
| **Member checking** | The process of sharing research analysis with participants to verify accuracy — a standard validation step in qualitative research |
| **SFIA** | Skills Framework for the Information Age — Level 5 = skilled practitioner, Level 6 = expert, Level 7 = inspire |
| **COM** | Commercial tool |
| **IH** | In-house built tool or automation suite |
| **OS** | Open source tool |
| **Atlas-ti** | A qualitative data analysis software tool used for coding and sentiment analysis |
| **H01–H12** | The twelve heuristic questions in the idea-t framework |
| **ISO 25010** | International standard for systems and software quality models |
| **ISO 25019** | Updated quality standard (2024) — identified as needing future alignment with the idea-t framework |

---

### Key References

- [11] ISO 25010 — Systems and software quality models
- [25] ISO 25019 — Updated quality standard (2024)
- [138] Nielsen — Ten Usability Heuristics
- [182] SFIA — Skills Framework for the Information Age
- [217] Petrie and Power — Heuristics evaluation methodology
- [218] Quinones and Rusu — Methodology for usability heuristics

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
