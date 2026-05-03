# Experiences with Tools to Support Testing

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

---

## 500-Word Précis

### Experiences with Tools to Support Testing

Software testers use a wide range of tools every day — from test management and defect tracking systems to automation frameworks and performance tools. These are known collectively as **TsST (Tools to Support Testing)**. The assumption behind providing these tools is straightforward: good tools make testing more efficient and effective. The reality, as this study found, is more complicated and more troubling.

This chapter answers the first research question: **RQ1.1 — What are testers' experiences with test tools?** Data was collected from 150 participants across conversations, expert interviews, practitioner workshops (in the UK and New Zealand), and four surveys. The analysis combined word frequency counts, thematic analysis, and sentiment coding, with independent validation by other researchers.

Three broad areas of concern emerged: **organisational and management issues**, mentioned by over 90% of participants; **technical issues**, mentioned by over 91%; and **usability and quality in use**, mentioned by over 98%. But within these three areas, two unexpected themes stood out.

The first unexpected finding was **emotional responses**. Around 30% of participants expressed emotion in their answers — even to straightforward factual questions about which tools they used. Negative emotions dominated: fear, frustration, and anger. One participant described tools as "scary." Another described feeling as if learning time had been "ripped away." The presence of these emotional responses — even in anonymous written surveys — points to the idea that tool problems affect more than productivity. They affect people's **lived experience (LX)** of their working lives.

The second unexpected finding was the **illusion of usability** — a concept developed during the analysis of this data. The illusion has three forms. First, tool designers treat usability as an attractive, easy-to-navigate interface, when usability is far more than that. Second, designers treat usability as the whole of quality in use, when technical attributes such as maintainability, portability, and reliability matter just as much to testers in practice. Third, tools are designed for a static user who never changes, when real testers grow, learn, and change their needs over time.

The most frequently mentioned specific concerns were around **operability** (tools that force testers to change their working style), **learnability** (both ease of getting started and support for long-term growth), and **portability** (tools that do not work smoothly across different environments). These concerns span both usability and technical quality attributes — confirming that usability is necessary but not sufficient.

The finding that tools affect testers' emotional wellbeing, combined with the discovery that both tool designers and purchasers appear to operate under an illusion of what usability really means, provides the motivation for the next stage of the research: a deeper investigation of who testers actually are, and an HCI-based framework to help tool designers and purchasers make better decisions.

**Key terms:** TsST (Tools to Support Testing); LX (Lived Experience); UX (User Experience); Illusion of Usability; Quality in use; Operability; Learnability; Shelfware

**Key references:** Wiklund et al. [32]; Bach and Bolton [31]; Johnson et al. [142]; Green and Petre [140]; Porter [8]

---

## 1000-Word Summary

### Experiences with Tools to Support Testing

---

### Reason for the Study

Software tools are expected to make testing faster and more effective. But a persistent and costly problem has long been recognised in the industry: tools are acquired but not properly used — a phenomenon known as **shelfware**. Despite this, almost no prior research had asked testers directly about their experiences with the tools they use every day.

This chapter addresses that gap, answering **RQ1.1: What are testers' experiences with test tools?** The hypothesis at the start was simple: ask testers, and they will tell you what is wrong. What actually emerged went further: not only did the data reveal practical problems with tools, it revealed emotional ones too — and, in the process of making sense of the data, a new concept: the **illusion of usability**.

The work in this chapter is grounded in and published in three papers: Evans et al. [38, 39, 40].

---

### Method

Data was collected across several stages, with analysis carried out incrementally so that each stage informed the next (illustrated in Figure 5.1 in the dissertation).

| Method | Participants | Context |
|---|---|---|
| Informal conversations | 4 | Industry conferences, UK and Germany |
| Semi-structured expert interviews | 8 | UK and New Zealand; SFIA Level 6–7 practitioners |
| Practitioner workshops | 31 | UKSTAR (UK); ANZTB SIG (New Zealand) |
| Surveys (4 separate surveys) | 111 | UK, Norway, New Zealand; online international |
| **Total** | **150** | |

*Table based on Table 5.1 in the dissertation*

Interview questions were deliberately open: "Tell me about your experiences with test tools and automation." Workshop participants used a usefulness-versus-effort matrix to plot their tools, and rated a chosen tool using the **NASA Task Load Index (NASA-TLX)** [183] — a validated measure of cognitive workload across six dimensions (mental demand, physical demand, temporal demand, performance, effort, and frustration level). Survey questions were non-hypothesis questions designed to elicit stories rather than confirm assumptions, modelled on methods from Johnson et al. [142].

Data analysis used word frequency counts, thematic analysis, and sentiment coding. Two rounds of coding by the researcher were followed by an independent replication by the supervisors, to validate the emotional response findings.

Ethics approvals ICT0292018 and 972116092021 were obtained. All participants were anonymised.

---

### Results

Participants raised concerns in three main areas, at the frequencies shown below:

| Area of Concern | % of Participants Mentioning |
|---|---|
| Organisational and management issues | >90% |
| Technical issues | >91% |
| Usability and quality in use | >98% |

*Based on combined analysis of all RQ1.1 data*

Within usability and quality in use, the most frequently mentioned attributes were:

| Quality Attribute | Participants Mentioning | Frequency of Mention |
|---|---|---|
| Operability | 93 | 250 |
| Learnability | 54 | 125 |
| User goals | 32 | 97 |
| UI aesthetics | 26 | 33 |
| Context coverage | 22 | 34 |
| Satisfaction | 12 | 24 |

*Based on Table 5.10 in the dissertation*

**[Note: Table 5.10 in the dissertation provides a full breakdown of quality-in-use and technical attribute codes and frequencies — this would be a valuable table to reproduce in full in any detailed publication.]*

Two unexpected themes emerged alongside the technical and organisational findings.

**Theme 1 — Emotional responses.** Approximately 30% of participants expressed emotion in their survey responses — even in answers to questions that did not invite emotional responses. Negative emotions (frustration, fear, anger) dominated, appearing in 30% of participant responses. Positive emotions (pride, satisfaction) appeared in 8%. Notably, some participants expressed emotion without identifying a specific issue — meaning that for some, the emotional impact of their tools extended beyond specific problems into a more general dissatisfaction with their working environment. This is the **lived experience (LX)** of tools at work: the effect on people's wellbeing and sense of professional identity, not just on task completion (after Porter [8]).

One participant described a tool as "scary." Another described feeling that learning time had been "ripped away." Another described too many tools as "a confusing cocktail." These were not fringe responses — they were representative of a significant portion of the 150 participants.

Emotional responses were validated through three rounds of coding. No correlation was found between the length of a response, vocabulary size, or number of issues raised, and the presence of emotional language — suggesting these responses were genuine expressions rather than artefacts of writing style.

**Theme 2 — The Illusion of Usability.** This concept emerged from the data and was not anticipated at the start of the research. The illusion of usability is the belief — held by tool designers and purchasers — that:

1. **Usability = a good-looking interface.** Tools that look attractive and are easy to get started with are assumed to be usable. In practice, deeper workflow support, learnability over time, and integration with other tools matter far more to experienced testers.

2. **Usability = quality in use.** Designers focus on usability without attending to the technical attributes — maintainability, portability, performance, and compatibility — that testers also depend on heavily.

3. **Users don't change.** Tools are designed for a static, defined user. In reality, testers grow, develop new skills, change team contexts, and take on new responsibilities. A tool that works for a beginner may frustrate an expert; a tool designed for an individual may fail a team.

---

### Discussion

The findings from RQ1.1 confirm and extend existing knowledge. Wiklund et al. [32] identified usability as an impediment to test automation. Johnson et al. [142] found that developers ignored tool warnings they could not understand. Green and Petre [140] showed that cognitive load from tool design affects programmers' performance. This research adds a new dimension: the emotional and lived experience impact of poor tool design on testers specifically.

The illusion of usability is not a criticism of individual tool designers or purchasers — it is a systemic gap. The tools that look best in demonstrations and evaluations are often those designed to look good, not to work well over extended, varied, and evolving use. A tester who uses a tool every day for three years has very different needs from a potential customer evaluating it for 30 minutes in a product demo. This gap between evaluation and real-world use is a key driver of shelfware.

The connection between emotional responses and tool quality raises important questions about workplace wellbeing, staff retention, and professional satisfaction. Addressing the illusion of usability is not just a technical design challenge — it is a people challenge.

---

### Conclusions

- Testers' experiences with their tools are frequently suboptimal, causing practical inefficiency, frustration, and emotional distress.
- Usability is the most frequently mentioned concern — but usability alone is not sufficient. Technical quality attributes are equally important.
- The illusion of usability — in its three forms — explains why tools so often fail to meet testers' real needs even when they pass initial evaluation.
- Emotional responses to tools are real, significant, and under-recognised in both tool design and tool acquisition practice.
- A superficial understanding of who testers are, and what they need, underlies all three forms of the illusion.

---

### Next Steps

The finding that tool problems are partly rooted in a poor understanding of who testers are leads directly to RQ1.2: **What are the characteristics of testers using test tools?** (Chapter 6). Addressing the illusion of usability requires first understanding the people experiencing it — their backgrounds, needs, communication styles, and working contexts. The results from this chapter also provide input into the evidence base for the idea-t framework (Chapter 8).

Future work identified in the dissertation (Appendix N) includes: a longitudinal study of testers' lived experiences with tools as organisations improve; and a multidisciplinary investigation of emotions among testers and other IT workers.

---

### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **TsST** | Tools to Support Testing — any tool used to support any testing activity, including automation tools, test management tools, defect trackers, and others |
| **LX** | Lived Experience — the effect of technology use extending beyond the immediate task into users' daily lives and wellbeing (after Porter [8]) |
| **UX** | User Experience — encompassing all aspects of end-user interaction with a product or service |
| **Shelfware** | Software tools acquired but not properly used |
| **Illusion of Usability** | The belief that usability equals a good-looking interface, and/or that usability alone equals quality in use |
| **Quality in use** | The degree to which a product or system meets the needs of users in a specific context of use; defined in ISO 25010 [11] |
| **Operability** | How well a tool can be operated by its users, including ease of control and flexibility |
| **Learnability** | How easily users can learn to use a tool, both initially and as they grow |
| **NASA-TLX** | NASA Task Load Index — a validated tool for measuring cognitive workload across six dimensions [183] |
| **SFIA** | Skills Framework for the Information Age — a framework for describing IT skills at seven levels (Level 1 Follow to Level 7 Inspire) |

---

### Key References

- [8] Porter, C. — Lived Experience and its relationship to tool use
- [11] ISO 25010 — Systems and software quality models, including quality in use
- [31] Bach and Bolton — Context-driven testing; testing "pain points"
- [32] Wiklund, Eldh, Sundmark and Lundqvist — Usability as an impediment to test automation
- [38] Evans et al. — Testers' lived experience with tools (published paper)
- [39] Evans et al. — Tool experiences: narrative study (published paper)
- [40] Evans et al. — Illusion of usability (published paper)
- [140] Green and Petre — Usability analysis of visual programming environments
- [142] Johnson et al. — Developers' experiences with static analysis tools
- [183] Hart — NASA Task Load Index

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
