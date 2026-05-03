# Understanding Who is Performing Testing

*This summary of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*

---



### Understanding Who is Performing Testing - short summary

<details close><summary>500-Word Précis</summary>

The first research study (Chapter 5) showed that tools frequently fail testers — and that part of the reason is that tool designers do not fully understand who testers are. This chapter investigates **RQ1.2: What are the characteristics of testers using test tools?**

An anonymous online survey of 78 industry practitioners explored their academic backgrounds, previous roles, hobbies, current responsibilities, communication styles, and career aspirations. The results are striking.

Testers come from a remarkably wide range of academic disciplines: IT and software engineering, but also arts, social sciences, sciences, medicine, philosophy, languages, boat building, and urban planning. Around 80% held a Bachelor's degree or above, but degree subjects varied enormously. Only around 17% had studied IT or software engineering specifically. Previous roles spanned development, requirements analysis, UX, product ownership, support, operations, risk management, and coaching.

When participants' interests and hobbies were compared against the **O*NET database** — which profiles IT workers as low in social and artistic interests — only **6% of tester participants** matched the IT worker stereotype. This compares with around 30% in a comparable study of general IT workers [175]. Testers are more artistic, more social, and more multi-interested than the stereotype suggests. The stereotype is not just inaccurate — it actively shapes recruitment and tool design in ways that exclude or underserve the majority of the testing community.

Current roles were complex and multi-faceted. Most participants held senior positions (SFIA Level 5 or above), combining testing with management, coaching, communication, risk assessment, and strategic leadership. Testing was described repeatedly as cognitively demanding and communication-intensive — not boring or repetitive.

Communication styles varied significantly: arts and social science graduates tended to respond conversationally and in stories; sciences and IT graduates responded tersely and technically. This variation has direct implications for how tools present and request information.

The key conclusion is that **a simple, small set of personas cannot represent the diversity of the testing community**. Any tool designed around a narrow, stereotypical tester — technical, developer-adjacent, visually-oriented — will serve the minority and frustrate the majority. Understanding this diversity is the essential first step towards better tool design, and it is the foundation on which the idea-t framework is built.

**Key references:** McChesney et al. [175]; Waychal et al. [83]; Capretz et al. [206]; Bolton [88]

**Key terms:** Persona; Stereotype; Heterogeneous; O*NET; SFIA (Skills Framework for the Information Age); TsST; Communication preferences; LX (Lived Experience)

</details>

---

## 1000-Word Summary

The longer summary below gives more detail on the reason for the study, method, results, themes arising, discussion, next steps arising from the research.


### Understanding Who is Performing Testing

---
<details close><summary>Reason</summary>

### Reason for the Study

The discovery study in Chapter 5 revealed that tool problems are partly rooted in a narrow understanding of who testers are. Tool designers appeared to be building for a stereotypical tester — technically expert, developer-adjacent, probably male — when the actual population using testing tools is far more diverse. Before a framework to improve tool design could be built, a clearer picture of who testers actually are was needed.

This chapter answers **RQ1.2: What are the characteristics of testers using test tools?** The work builds directly on the findings of Chapter 5, using themes that emerged from those data to shape the survey design. It is published in two papers: Evans et al. [41, 43].

</details>

---



<details close><summary>Method</summary>

### Method

An anonymous online survey was conducted with 78 industry practitioners. Ethics approval ICT202300127 was obtained. The survey was promoted via conference presentations, webinars, LinkedIn, online discussion groups, and direct contacts, giving an international, self-selected sample.

| Characteristic | Detail |
|---|---|
| Total participants | 78 |
| Gender | 46% male, 53% female, 1% non-binary |
| Age | Over 90% between 25 and 64 |
| Geography | Europe (main), North America, Asia, South America, Australasia; no Africa |
| Survey period | September 2021 – July 2022 |

*Based on Tables 6.1 and 6.3 in the dissertation*

The survey used a mix of closed demographic questions and open, non-hypothesis questions. It covered: academic background, professional training, previous IT roles, current role and responsibilities, approaches and techniques used in testing, hobbies and interests, and career aspirations. It was piloted with four testers, including native and non-native English speakers, before use.

Data analysis used quantitative frequency analysis for closed questions and qualitative thematic analysis for open responses, with coding emerging from the data rather than being imposed in advance. The demographic profile of the sample was validated against five industry reports and conference media packs [22, 177, 178, 179, 180] to check representativeness.

</details>

---

<details close><summary>Results</summary>

### Results

**Academic backgrounds.** About 80% of participants held a Bachelor's degree or above. But the subjects studied were varied: approximately 10% had arts degrees, 14% social sciences, 25% sciences, and 17% IT or software engineering. Around 40% did not specify a degree subject, or had no degree, including participants who had entered testing from entirely non-IT careers. Previous roles ranged across development, requirements analysis, UX design, product ownership, support, operations, risk, project management, and coaching.

**Non-IT backgrounds.** Participants mentioned backgrounds in medicine, philosophy, languages, technical writing, theatre, music, urban planning, landscape gardening, boat building, and carpentry. One expert interviewee from Chapter 5 described a deliberate recruitment policy of looking for candidates who played musical instruments or embroidered — valuing attention to detail, patience, and persistent learning. These diverse backgrounds were seen by participants as assets, not disadvantages.

| Academic Subject | % of Participants | Characteristic Roles and Styles |
|---|---|---|
| Arts | ~10% | Technical and management roles; conversational response style |
| Social Sciences | ~14% | Technical, management, and consultancy roles; big-picture thinking |
| Sciences | ~25% | Technical and management roles; terse, list-based response style |
| IT / SWE | ~17% | Technical-focused roles; detailed technical responses |
| Not stated or pre-Bachelor's | ~42% | Management and non-technical roles; expansive, conversational |

*Based on Table 6.5 in the dissertation*

**Roles and responsibilities.** Most participants held senior roles — over 50 of the 78 were assessed as working at **SFIA Level 5 or above** (skilled practitioner or above). Job titles included Test Manager, Quality Engineer, Software Engineer in Test, Quality Coach, Test Architect, Director of Quality, and Head of Testing. Most participants described multi-functional roles: combining testing with management, coaching, stakeholder communication, risk assessment, and strategic planning.

Testing was described repeatedly as cognitively demanding. Responsibilities mentioned included: automation design; risk assessment; requirements and design review; exploratory testing; performance and security testing; test programme management; coaching teams; communicating with C-level stakeholders; and running quality improvement programmes. This does not resemble a boring, repetitive job.

**Hobbies and interests.** Participants described a wide range of hobbies: over 60% mentioned outdoor and sporting activities; 45% making, performing, writing or playing music; 41% reading and self-directed learning. When these were compared against the **O*NET profile for IT workers** — which predicts low social and low artistic interests — only **6% of tester participants** matched the IT worker stereotype. This compares to approximately 30% in a study of general IT workers [175].

This finding is significant. The IT worker stereotype shapes both recruitment advertising and tool design. If tool designers assume their users are stereotypical IT workers — low in artistic and social interests, comfortable with dense technical interfaces and minimal social features — they will design tools that serve the minority and frustrate the majority.

**Communication styles.** Qualitative analysis of how participants answered open questions revealed marked differences in communication style by academic background. Arts and social science graduates wrote conversationally, in stories and with context. Sciences and IT graduates tended to be terse and technical. This variation matters for tool design: a tool that presents information in dense technical formats will be harder to use for participants from arts and social science backgrounds, and vice versa. Heuristic H04 (Communication preferences) in the idea-t framework is specifically designed to address this.

**Aspirations.** Career aspirations ranged from developing specific technical skills, to leading large teams, to C-suite roles (CTO, CQO). Testing is not seen as a career dead-end by those doing it, even if it is sometimes perceived that way from the outside.

</details>

---

<details close><summary>Discussion, Conclusions and Next Steps</summary>

### Discussion

The findings confirm and extend work by Waychal et al. [83] — that testing is a high-cognitive-skill activity — and by McChesney et al. [175] — that IT workers do not match the stereotypes commonly used in recruitment. This study goes further: testers are *more* non-stereotypical than IT workers generally, and the implications for tool design are specific and practical.

A particularly interesting finding was the experience profile of the most senior participants. The eight directors and heads of department in the sample showed a higher proportion with no development experience and no UX experience than the broader group of senior practitioners. While the sample is too small to generalise, this raises the question of whether senior decision-makers responsible for tool acquisition and budget may lack first-hand experience of the technical and UX challenges their teams face day-to-day.

***"The director and head of department participants showed a slightly different pattern — a larger proportion of people with no development, and no UX experience." The dissertation notes the sample (N=8) is too small for definitive claims. Is this finding intended to be highlighted in publications, given the limitation? Please confirm.***

The diversity of communication styles found across different academic backgrounds also has implications beyond tool design — for team collaboration, test documentation, and how tools request and present information to users.

---

### Conclusions

- Testers are a highly heterogeneous group, with backgrounds, interests, and communication styles far broader than the IT worker stereotype suggests.
- Only 6% of tester participants in this study matched the O*NET IT worker stereotype — compared with approximately 30% of general IT workers.
- Testing requires high cognitive skill, strong communication, and multi-disciplinary knowledge — it is neither simple nor repetitive.
- A simple, small set of personas cannot represent the diversity of the testing community.
- Tool designers who assume a narrow, stereotypical tester will produce tools that fail the majority of their actual users.
- Understanding this diversity is the foundation of the idea-t framework.

---

### Next Steps

The findings from RQ1.2 directly inform RQ1.3 (Chapter 7 onwards): if testers are too diverse to be captured in a fixed persona set, what approach can help tool designers and purchasers think more carefully about who their real users are? The answer developed in this research is a framework of heuristic questions — the idea-t framework — which provides structured prompts to help teams build their own, context-specific understanding of their users, rather than relying on generic or stereotyped assumptions.

Future work identified in the dissertation (Appendix N) includes: extending the survey to geographic regions not represented (particularly Africa and South America); a longitudinal study tracking mid-level testers through to end of career; and a meta-study of developer experience literature, to compare emotional and experiential patterns across IT roles.

</details>

---


<details close><summary>Glossary, Abbreviations, References</summary>


### Glossary and Abbreviations

| Term | Meaning |
|---|---|
| **TsST** | Tools to Support Testing — any tool used to support any testing activity |
| **LX** | Lived Experience — the effect of technology use extending beyond the immediate task into users' daily lives and wellbeing |
| **Persona** | A fictional character representing a group of users, used in design to guide decisions about who a product is for and what they need |
| **Stereotype** | An oversimplified, generalised image or idea of a particular type of person — in this context, the assumption that IT workers (and testers) share a narrow set of characteristics |
| **Heterogeneous** | Made up of different and diverse elements — used here to describe the wide variety of backgrounds, interests, and characteristics found among testers |
| **O\*NET** | The US Occupational Information Network — a database profiling the characteristics and interests associated with different occupations, used here to compare testers against the IT worker profile |
| **SFIA** | Skills Framework for the Information Age — a framework for describing IT and digital skills at seven levels, from Level 1 (Follow) to Level 7 (Inspire) |
| **RQ1.2** | Research Question 1.2: What are the characteristics of testers using test tools? |

---

### Key References

- [22] World Quality Report — industry survey used for demographic comparison
- [41] Evans et al. — Breaking Tester Stereotypes: who is testing and why it matters (published paper)
- [43] Evans et al. — The software testing community and IT stereotypes (published paper)
- [48] ISTQB — International Software Testing Qualifications Board certification scheme
- [62] Weinberg — "Testing is harder than developing" (tweet cited in dissertation)
- [76] RST — Rapid Software Testing (training syllabus)
- [83] Waychal et al. — Study of testing practitioner testimonials; testing as high-skill work
- [88] Bolton — Testing as cognitively challenging work
- [175] McChesney et al. — IT worker stereotypes and diversity
- [206] Capretz et al. — Personality types in software engineering

</details>

---

*This is a summary of part of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
