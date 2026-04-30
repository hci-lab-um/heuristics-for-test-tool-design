# Precis of Isabel Evans' Doctoral Dissertation
## A Framework to Support Test Tool Design and Acquisition
*This precis of material from Isabel Evans' dissertation was produced with the help of Claude (Claude Sonnet 4.6, Anthropic, April 2026)*
Precis word count: 3000 words approx., Dissertation word count: 119,100 words approx.
This precis provides a chapter-by-chapter overview of the entire dissertation.
The research that resulted in the idea-t framework held on this [GitHub repository](https://github.com/hci-lab-um/heuristics-for-test-tool-design/blob/main/README.md).
The purpose of this summary is to allow you to decide which parts of the dissertation – if any – you want to read. **Reading the dissertation is not necessary for using idea-t, it is made available for transparency and to allow deep background reading for those who want it.**
The dissertation may be downloaded from the [University of Malta Open Access Repository OAR@UM as a PDF]( https://www.um.edu.mt/library/oar/handle/123456789/144337)
A 150-word precis for each chapter is below.
## Chapter 1: Introduction
<details> <summary> 150-word precis</summary>

Software testing is vital to successful software delivery, and tools to support testing (called TsST — Tools to Support Testing) are intended to make testing more efficient and effective. However, tools are frequently acquired but not used, or used but failing to deliver — a problem known as **shelfware**. Isabel Evans' doctoral research addresses the question: *"How can HCI (Human-Computer Interaction) techniques help with the design of test tools?"*

This question breaks into three sub-questions: What are testers' experiences with tools? What are the characteristics of the people doing testing? And how could HCI design heuristics inform tool design? The research is grounded in the real-world experiences of industry practitioners, and places people — not technology — at the centre. The dissertation is structured around answering these three questions, leading to the development of the **idea-t framework** of heuristics.

</details>

**Key abbreviations:**
- **TsST:** Tools to Support Testing
- **HCI:** Human-Computer Interaction
- **idea-t:** Influencing the Design, Evaluation and Acquisition of Tools for Testing
- **Shelfware:** Software tools obtained but not used

## Chapter 2: Literature Review

<details> <summary> 150-word precis</summary>

The literature review establishes the background to the research across two main areas: software testing and its tools, and Human-Computer Interaction (HCI). Testing has multiple competing definitions and viewpoints — from highly analytical and standards-based approaches to context-driven and agile approaches — and this diversity shapes both how testing is done and what tools are needed.

Research into test tools has focused mainly on automation, and largely from a technical perspective. Studies of usability challenges with developer tools show that poor design leads to frustration, abandonment, and security risks. The review identifies a clear **research gap**: no prior work had applied HCI methods specifically to the tools used by testers, nor had it investigated testers' lived experiences with those tools. This gap motivates the three research questions and the development of the idea-t framework.
The central research question is: **"How can HCI techniques help with the design of test tools?"** HCI — Human-Computer Interaction — is the academic and professional discipline that studies how people interact with technology, and how to design technology that works well for people.  The research breaks this central question into three parts:

1. **RQ1.1** — What are testers' experiences with test tools?
2. **RQ1.2** — What are the characteristics of testers using test tools?
3. **RQ1.3** — How could HCI design heuristics inform test tool design?

</details>


**Key reference:** Wiklund et al. [32] identified usability as an impediment to test automation and called for practical, industry-useful solutions.

## Chapter 3: Theoretical Framework

<details> <summary> 150-word precis</summary>

The theoretical framework places **people** at the centre of the research. Testers work within complex systems — organisations, projects, technical environments — and both the systems and the people within them affect how testing is done and how tools can support it.

The framework draws on three sources: HCI (to understand people and their goals), soft systems thinking (to place people at the centre of systems), and design thinking (to embrace multiple viewpoints and use iterative prototyping). It also explores the relationship between **quality viewpoints** (manufacturing, product, user, value, transcendent) and **testing viewpoints**, showing that these intersect in complex ways. A key concept is the **levels of automation** — from tools that assist humans, through to fully automated systems — and how these affect the role and experience of the tester. The framework sets up the conditions for a mixed-methods, people-centred research methodology.

</details>


**Key terms:** Soft systems thinking; Design thinking; Quality in use; Levels of automation

## Chapter 4: Methodology

<details> <summary> 150-word precis</summary>

The research uses a **mixed methods** approach, combining qualitative and quantitative methods to answer its three research questions. The philosophical stance is **pragmatism**, drawing on interpretivism and critical realism — meaning that the research values practitioners' stories and experiences as genuine knowledge, while remaining open to multiple interpretations of reality.

Data was collected through interviews, workshops, surveys, expert reviews, case studies, and a retrospective analysis, involving nearly 300 participants across eight years. The research is an **"of me"** study — the researcher is also a member of the testing community — and steps were taken throughout to reduce bias and maintain validity. All studies were conducted under University of Malta ethical guidelines. The main output, the idea-t framework, was developed iteratively through prototyping, with input from both practitioners and experts at every stage.

</details>


**Key terms:** Mixed methods; Pragmatism; Interpretivism; Critical realism; Abductive reasoning; "Of me" research

## Chapter 5: Experiences with Tools — Discovery Study


This chapter investigates **RQ1.1: What are testers' experiences with test tools?** 

<details><summary> 150-word precis </summary>

Through interviews, workshops and surveys with over 140 industry practitioners and experts, two unexpected themes emerged alongside the expected organisational and technical challenges.


The first is the **emotional impact** of tools — nearly a third of participants expressed emotion in their responses, mostly negative: fear, frustration, anger, and occasionally pride. The second is the **"illusion of usability"** — a concept new to this research. This illusion has three forms: treating usability as just an attractive interface; assuming usability alone is enough for a good user experience; and failing to support users as they grow and change. Usability problems were the most frequently mentioned concern, but the research shows that usability — while necessary — is not sufficient. Quality in use, including technical attributes and workflow support, is equally important.

</details>

**Key concept:** Illusion of Usability; Quality in use; Lived Experience (LX)

## Chapter 6: People Who Are Testing — Discovery Study

This chapter investigates **RQ1.2: What are the characteristics of testers using test tools?** 

<details> <summary> 150-word precis</summary>

An anonymous online survey of 78 industry practitioners explored their backgrounds, qualifications, hobbies, roles, approaches to testing, and communication preferences.

The key finding is that testers are a **non-stereotypical and heterogeneous group**. They come from a wide range of academic backgrounds — including arts, social sciences, medicine, philosophy, and boat building — and hold a much broader range of interests than the standard IT worker stereotype. Only 6% of participants matched the O*NET stereotype for IT workers, compared with 30% in a comparable study of other IT workers. Testers cannot be represented by a small, simple set of personas.

This finding has direct implications for tool design: if designers assume a narrow, stereotypical user, they will build tools that fail the majority. The idea-t framework is designed to help overcome this.

</details>




**Key concept:** Personas; Stereotyping; Heterogeneous user group; SFIA

## Chapter 7: Framework Development and Evaluation

This chapter describes the work to turn the research findings from Chapters 5 and 6 into the **idea-t framework**.

<details> <summary> 150-word precis</summary>

The chapter begins by explaining why heuristics were chosen as the format — the diversity and complexity of testers and their contexts make a single set of pre-defined personas impossible. Instead, heuristic questions allow designers and purchasers to investigate their own context. It is the start of the work to investigate **RQ1.3 — How could HCI design heuristics inform test tool design?**

The chapter covers the development of the heuristics through iterative **prototyping** with industry experts and practitioners, drawing on literature about heuristics design and validation. A key contribution is the **"shape of heuristics" model** — a study of how heuristics can be expressed (textual, pictorial, or conceptual) and how directive they should be (asking, prompting, or telling). The result was a preference for **textual, asking-style** heuristics — questions that provoke thought rather than prescribe answers.

</details>


**Key concept:** Heuristics; Shape of heuristics; Iterative prototyping; Design thinking

## Chapter 8: The idea-t Framework

This chapter contributes to answering **RQ1.3** — How could HCI design heuristics inform test tool design?

<details> <summary> 150-word precis</summary>

This chapter describes the **idea-t framework** in full. The name stands for "Influencing the Design, Evaluation and Acquisition of Tools for Testing," and comes from the Maltese word *ideat*, meaning ideas.

The framework contains **twelve heuristic questions** grouped into three themes: **Why?** (one heuristic about the purpose of the tool), **Who?** (five heuristics about the people who will use or be affected by the tool), and **Context?** (six heuristics about where, when, and how the tool will be used). Each heuristic is supported by a keyword, a quick-start prompt, sub-questions, explanations, research evidence, and suggested activities. The framework also maps heuristics to **ISO 25010 quality attributes**, helping users connect design decisions to quality outcomes.

The framework is designed to be used flexibly — in any order, with any subset of heuristics, tailored to context. It is published openly on GitHub under a Creative Commons licence.

</details>



**Key terms:** idea-t; Heuristics; Quality in use; ISO 25010; Quality attributes; TsST

## Chapter 9: Formative Case Studies

This chapter contributes to answering **RQ1.3** — How could HCI design heuristics inform test tool design?

<details> <summary> 150-word precis</summary>

Five formative industry case studies evaluated and refined the idea-t framework in real-world settings. Conducted across four organisations, the case studies covered a range of contexts: evaluating a vendor tool, reviewing in-house automation suites, designing new features for a commercial tool, planning a customer tool evaluation, and reviewing an enterprise tooling strategy.

Each case study used a diary-based data collection method, followed by analysis and member-checking. The framework was improved after each study, moving from v1.01 to v1.06. Sixty issues were raised and resolved. Benefits reported included improved inter-team communication, money saved by avoiding an unnecessary tool purchase, better understanding of automation suite purposes and audiences, and new strategic insights.

The studies confirmed that the framework is understandable and useful across diverse contexts — but also highlighted the need for faster entry points, clearer navigation, and training materials to support adoption.

</details>


**Key terms:** Formative evaluation; Case study; idea-t; Member checking; TsST

## Chapter 10: Retrospective Evaluation

This chapter contributes to answering **RQ1.3** — How could HCI design heuristics inform test tool design?

<details> <summary> 150-word precis</summary>

The retrospective evaluation asked: **if the idea-t framework had been used at the design stage, could it have prevented customer issues?** Working with the same tool vendor organisation from Case Study 3, a sample of 100 customer issues (improvement requests, support queries, and user questions) raised over 18 months was analysed against the heuristics.

The participant assessed each issue for importance (high, medium, or low) and for the applicability of each heuristic. The finding was that approximately **40% of issues had one or more heuristics that were applicable** and could have positively influenced design decisions — including both high-importance issues. The heuristic most frequently applicable was H08 (Workflows), followed by H04 (Communication preferences) and H06 (Learning preferences).

While no causal claim is made, the findings are indicative: earlier use of the idea-t framework at the design stage has the potential to reduce post-release customer issues.

</details>


**Key terms:** Retrospective analysis; idea-t; Quality in use; Customer issues; TsST

## Chapter 11: Summative Expert Review

This chapter contributes to answering **RQ1.3** — How could HCI design heuristics inform test tool design?

<details> <summary> 150-word precis</summary>

Seven expert reviewers — drawn from testing, test tool design and building, tool acquisition, HCI, and accessibility — reviewed the idea-t framework in its most developed form (v1.07). Reviewers were selected to represent a range of viewpoints, expertise levels, and industry roles. Each conducted an independent review followed by a discussion with the researcher.

Overall sentiment was strongly positive: nearly **70% of coded comments were positive**. Reviewers welcomed the evidence base, the non-prescriptive approach, and the practical usefulness of the heuristics. They particularly valued heuristics that challenged their existing assumptions. Improvement suggestions focused mainly on **structure and navigation** of the GitHub repository, and on providing the framework in additional media (poster, book, PDF, video).

Key refinements were made to heuristic wording, theme groupings, navigation aids, and a draft poster. Further improvements to media and structure are identified as future work.

</details>




**Key terms:** Summative evaluation; Expert review; idea-t; Heuristics; Quality in use

## Chapter 12: Discussion

<details> <summary> 150-word precis</summary>

The discussion chapter brings together the findings from all three research questions and evaluates them against each other and against existing frameworks. Key conclusions are that testers' **lived experiences** are genuinely affected by their tools; that an **illusion of usability** has been limiting tool design; that testers are a **heterogeneous, non-stereotypical group** that cannot be served by simple personas; and that the **idea-t framework** provides a practical, evidence-based response to these challenges.

The chapter also applies the idea-t framework to itself — a self-test that reveals both strengths and gaps. It compares idea-t with other frameworks including Nielsen's Ten Heuristics, the 5 W's and H, the Zachman Framework, Soft Systems CATWOE and LUMAS, the Automation in Testing (AiT) framework, and testing discussion card sets. Each comparison reveals what idea-t adds and where it overlaps.

</details>


**Key concept:** Illusion of Usability; Lived Experience; Heterogeneous; idea-t; Heuristics

## Chapter 13: Conclusion

<details> <summary> 150-word precis</summary>

The conclusion summarises the four key findings of the research: testers' lived experiences are significantly affected by their tools; an illusion of usability has been limiting tool design; testers are a non-stereotypical and heterogeneous group; and the idea-t framework provides a practical, evidence-based response. Five contributions to knowledge are claimed: the idea-t framework (major), understanding of testers as a non-stereotypical group (minor), understanding of testers' lived experience (minor), the illusion of usability concept (minor), and the shape of heuristics model (minor).

The chapter also reflects on the limitations of the research (geographic gaps, time constraints of a PhD study) and identifies extensive future work. The researcher reflects on the personal impact of eight years of doctoral study, and the surprise of findings that consistently challenged her own 40 years of industry experience.

</details>


**Key concept:** idea-t; Illusion of Usability; Contributions to knowledge; Future work; Reflective practice

## Appendices

### Background Material (Appendices A and B)

Appendices A and B provide extended background material supporting the main text. 

<details> <summary> 150-word precis</summary>

**Appendix A** covers the definition, history, costs, and benefits of software testing, tracing its development from the 1950s to the present day. It describes how definitions of testing have evolved across decades and testing viewpoints, and discusses the quality viewpoints that affect how testing is understood and measured.

**Appendix B** covers the relationship between people, technology, and systems. It introduces systems thinking, the elements of a system (Nemeth [171]), complexity theory (Cynefin [185, 242]), organisational maturity models (CMM, TMMI, TAIM, UMM), and the SFIA skills framework. It also covers soft systems methodology (Checkland [37]) and design thinking in more depth, providing theoretical grounding for the research approach.

Together, these appendices provide essential context for readers less familiar with software testing or systems thinking.

</details>


**Key references:** Gelperin and Hetzel [230]; Nemeth [171]; Snowden [185, 242]; Checkland [37]

### Methodology Background (Appendix C)

Appendix C provides additional background on the research philosophy and methodology. 

<details> <summary> 150-word precis</summary>

It compares three philosophical positions — **critical realism**, **interpretivism**, and **pragmatism** — and explains how all three contribute to the research stance. Critical realism acknowledges that reality is structured and layered; interpretivism values participants' stories as genuine knowledge; pragmatism connects research to practical improvement.

The appendix also distinguishes between **data-driven research** (drawing on primary data from participants and secondary data from the literature) and **researcher-driven research** (using concept maps, diagrams, and models developed by the researcher). Both approaches were used at different stages of the study.

The "of me" and "plus one" nature of the research — the researcher is a member of the testing community, and the work builds on related prior research — is acknowledged, along with the steps taken to reduce bias.

</details>


**Key terms:** Critical realism; Interpretivism; Pragmatism; Abductive reasoning; "Of me" research; Mixed methods

### Data Collection Instruments (Appendices D, E, and F)

Appendices D, E, and F contain the data collection instruments used in the first two research studies.

<details> <summary> 150-word precis</summary>

**Appendix D** provides the interview questions, workshop scripts, and survey questions used to investigate RQ1.1 (testers' experiences with tools). These include the semi-structured interview prompts, the UKSTAR workshop exercises (using a usefulness-versus-effort matrix and the NASA Task Load Index [183]), and the survey questions for both the UKSTAR and ANZTB workshops.

**Appendix E** provides the full survey used to investigate RQ1.2 (characteristics of testers), covering demographics, background, work profile, approaches and tools, and open questions.

**Appendix F** provides data tables showing participants' years of experience across different IT roles (testing, development, requirements, UX, operations, management, etc.), supporting the analysis in Chapter 6.

These appendices support replication of the research methods.

</details>


**Key terms:** Semi-structured interview; Workshop; Survey; NASA-TLX; UKSTAR; ANZTB

### Heuristics Prototyping (Appendices G and H)

Appendices G and H document the prototyping work done to develop the heuristics at the heart of the idea-t framework.

<details> <summary> 150-word precis</summary>

**Appendix G** covers the "shape of heuristics" study — a small pilot with five UX practitioners that tested nine combinations of heuristic format (textual, pictorial, conceptual) and directiveness (asking, prompting, telling). The result was a clear preference for textual, asking-style heuristics. The appendix includes the slides used in the pilot and the scoring results.

**Appendix H** provides the data collection instruments for the content prototyping — the review instructions sent to expert reviewers of the heuristics, and an example of the prototype heuristics and checklist questions at an early stage of development. These show how the heuristics evolved from broad thematic groupings into the twelve focused questions of the final framework.

</details>


**Key terms:** Heuristics; Shape of heuristics; Prototyping; Expert review; Textual-asking; Directiveness

### The idea-t Framework in Detail (Appendix I)

<details> <summary> 150-word precis</summary>

**Appendix **I provides the full structure of the idea-t framework, including all twelve heuristics with their keywords, sub-questions, guidelines, activities, and quality attribute links. It also contains a worked example of how the heuristics can be used to develop a first set of **personas** using a classification tree approach.

A key feature is the **quality attributes section**, which maps each heuristic to the relevant ISO 25010 quality in use and product quality attributes, ordered by their frequency and importance in the research data. This allows users to approach the framework from two directions: from a heuristic to find relevant quality attributes, or from a quality attribute to find the relevant heuristics.

The appendix concludes with a reproduction of the **idea-t poster** (Figure I.7), a one-page visual summary of the framework designed for quick reference. The poster can be found in the [Downloads folder]( https://github.com/hci-lab-um/heuristics-for-test-tool-design/blob/main/Downloads/About-Downloads-Folder.md) in this repository.

</details>


**Key terms:** idea-t; Heuristics; Quality attributes; ISO 25010; Persona; Classification tree; Poster


### Case Studies and Evaluations (Appendices J, K, and L)

Appendices J, K, and L provide the detailed records of all the evaluative studies.

<details> <summary> 150-word precis</summary>

**Appendix J** contains the full case study documentation for all five formative case studies, including diary forms, research environment descriptions, action plans, fieldwork notes, results, and reflections. It also includes process diagrams showing how tool workflows changed as a result of the heuristics.

**Appendix K** contains the detailed methodology and results of the retrospective analysis, including the action planning, fieldwork analysis, and the data tables showing issue importance and heuristic applicability.

**Appendix L** contains the full biographies and verbatim summary verdicts of the seven expert reviewers, along with all the data tables from the sentiment analysis of their comments. Reviewer names are used in the dissertation (with their consent) but are replaced by ER1–ER7 in these summaries.

</details>



**Key terms:** Formative case study; Retrospective analysis; Expert review; Diary; Member checking; idea-t

### Applying and Extending idea-t (Appendices M and N)

<details> <summary> 150-word precis</summary>

**Appendix M** documents the self-test of the idea-t framework — applying its own heuristics to itself as a tool. Working through all twelve heuristics, the appendix shows what the framework reveals about its own purpose (Why?), its users (Who?), and its context of use (Where? When? For how long?). The exercise confirms that the framework works — it provokes genuine insights and reveals gaps — while also highlighting that it takes effort and benefits from a champion for adoption.

**Appendix N** lists potential future research projects, including: extending the geographic reach of the research; applying the methods to other tool domains (developer tools, security tools); investigating AI in testing tools; updating the framework to the revised ISO 25019 quality attributes standard; developing training materials; and a longitudinal study of tester career development.

</details>


**Key terms:** idea-t; Self-test; Future work; ISO 25019; AI in testing; Training materials

*This is a summary of Isabel Evans' dissertation published on the University of Malta Open Access Repository OAR@UM. The full dissertation may be downloaded as a PDF from https://www.um.edu.mt/library/oar/handle/123456789/144337*
*This precis was produced in draft using Claude (AI) and then edited by Isabel.*
