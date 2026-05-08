<a name="TopofPage"></a>
# About the Research and the Researchers
[◄ Go to ReadMe](../README.md)

This page is about the research behind the heuristics, information about the researchers, and also has links to videos, academic papers and other resources.

## Presentation slides, videos and articles about the Research
<details openclose>
<summary>Click for Presentations, Videos and Articles</summary>

Podcasts:
- [Chat with Richard Seidl about stereotyping](https://youtu.be/blPHnprdbzE)
- [Chat with Lisa Crispin and Janet Gregory about job titles](https://www.youtube.com/watch?v=NaH_6iE6rW0) 

If you want a brief summary, here is [an article "Just a tester?"](https://www.womenwhotest.com/2023/04/14/just-a-tester-a-report-part-way-through-data/) from 2023 which summarises the research to that point and highlights of the findings. There are also [summaries on Isabel's blog](https://isabelevansconsultancy.wordpress.com/) reporting on research progress.

Here are links to some earlier videos about the research. They are each about 30-50 minutes long.

1. [Talk about the research from 2020 YouTube video): "Illusions, Magic and Test Automation"](https://www.youtube.com/watch?v=EAEG3CzZzVY) from Code Camp Romania.
2. [Report on the research from 2022: "Who is Testing? Do tools help and support them?" (YouTube video)](https://www.youtube.com/watch?v=JhmZpnZO_ys) from TestMu conference.
3. [Webinar from 2022 "Who is testing?"](https://www.bigmarker.com/techwell-corporation/Who-Is-Testing-A-Reflection-Part-Way-Through-Data-Analysis) from Techwell.
4. [Interview with Agiletest (YouTube video)](https://www.youtube.com/watch?v=0fZlOqjmZqQ) from Agiletest Invites.
5. [Interview - PhD Unpacked - programme 7](https://www.um.edu.mt/services/campus1037/ondemand/education/phdunpacked/) A University of Malta Campus Radio podcast, thirteen-episode series dedicated to the experiences of PhD students.

Other presentation slides from talks at industry conferences are in the [Downloads folder](../Downloads).
  
</details>



[Back to Top](#TopofPage)

## The Research - a brief history 

<details close>
<summary>Click for Background</summary>

###	Background
After nearly four decades working in the IT industry, mainly in software testing, latterly as a consultant and trainer, Isabel had observed that teams and organizations didn’t have the successes they anticipated with adoption of tools to support testing. Wanting to understand the blockers to test tool adoption and what might overcome these, with an initial idea that improving the usability of tools would help people adopt them and use them successfully, she started a post-graduate study at University of Malta to give a structure for researching the ideas. Isabel worked with Prof. Chris Porter and Prof. Mark Micallef who are her academic supervisors, and with Dr. Julian Harty to contributed to work on several of the papers arising from the research.  Isabel graduated with a PhD in March 2026.

</details>


[Preprints of published papers are listed here](preprints.md) and a summary of the research journey story so far is below. 

<details close>
<summary>Click for Story Through the Research </summary>

###	Story Through the Research

Links to the published versions of the papers are below, and you can also [download a preprint draft](preprints.md) if you cannot access the publishers' libraries.

**Stories about experiences with test tools:** In the initial stage of the research we went out to industry with a simple question “tell me a story about your experiences with test tools” via interviews, surveys and workshops, and was startled by the results. These were:
1.	Testers’ lived experience is adversely affected by poor tools (Papers: “[Stuck in Limbo with Magical Solutions](https://www.scitepress.org/Link.aspx?doi=10.5220/0009091801950202)” and “[Scared, Frustrated and Quietly Proud](https://dl.acm.org/doi/abs/10.1145/3452853.3452872)”). 
2.	Usability was the major concern about the tools, followed by organizational impacts on tool use. All the other quality attributes of the tool made up about one third of the total concerns.
3.	Attempts to improve usability of tools had sometimes made the overall experience of the tool worse (Paper: “[Test Tools: An Illusion of Usability?](https://ieeexplore.ieee.org/abstract/document/9155938)”):
    -	Usability was not enough by itself – other quality attributes are sometimes forgotten;
    -	Usability was often treated superficially by making the interface attractive but not improving workflows;
    -	Understanding of personas in testing was sometimes superficial – there was not an understanding of the range and type of people doing testing.

**Finding out who is testing software:** To better understand the potential in tester persona development, we asked "Who is testing?" in a further detailed survey which provided evidence of the heterogenous nature of the testing community, and the wide range of people’s characteristics, contexts, approaches, and requirements. The data indicated that the people designing tools may benefit from a framework to help them better understand testers and the contexts for testing. A paper "Breaking Tester Stereotypes: who is testing and why it matters" was presented in July 2024 at the BCS HCI 2024 conference and has been published by them, and a journal paper "The Software Testing Community and IT Stereotypes: a study with industry professionals" is published in IWC journal 2025. There is a [summary on a blog](https://isabelevansconsultancy.wordpress.com/2024/07/26/research-report-breaking-tester-stereotypes-who-is-testing-and-why-it-matters/) and [preprints on this repository](preprints.md).

**Encapsulating findings in a usable summary:** Based on the data analysed so far, we are working on building a set of heuristics for tool designers to use when designing test tools. Iterating through a series of reviews of versions of the heuristics both with UX experts and practitioners, and with test experts and practitioners. The draft heuristics are [listed on this repository](README.md), with their explanations and suggested activities.

**Shaping the Heuristics:** First, we needed to understand how heuristics should be developed and what they look like. Should they be like Nielsen's Ten Heuristics? Like Bach and Bolton's FEW HICCUPS? Something different? We looked at many examples to see how heuristics are displayed and discovered that they have different levels of directedness and also that they are displayed in different formats. Working with UX practitioners and experts, we trialed and refined various styles for the heuristics and chose a format - the short question with explanation - used in this repository. 
Based on that format, we then set out to design a set of heuristic questions, grounded in the research data collected earlier.

**Evaluating the Heuristics - expert reviews:** We took versions of the heuristics to test experts and practitioners to understand if the content of the heuristics indicate anything useful about the people who will use the test tools. That included asking someone who had built a tool whether the heuristics would have changed their thinking when designing/building the tool, and a review with an accessibility expert.
We updated the heuristics based on the review comments, in an iterative process.

**Evaluating the Heuristics - case studies:** We undertook an iterative build-review-refining of the heuristic set content through industry case studies to evaluate the heuristics in use.
The case study results were used to refine the heuristics based on comments and observations of them in use.
This GitHub repository is here to support the case studies and capture the heuristics and supporting information.


</details>

<details><summary>Click here for information about Isabel's dissertation and links to summaries of the chapters and studies</summary>

### The Completed Dissertation: `A Framework to Support Test Tool Design and Acquisition'

The dissertation that supported the award of Isabel's PhD is long... nearly 120,000 words! So here is a link to a [precis of around 3000 words](Dissertation-Precis.md). The precis provides a chapter-by-chapter overview of the entire dissertation.

The purpose of this summary is to allow you to decide which parts of the dissertation – if any – you want to read. **Reading the dissertation is not necessary for using idea-t, it is made available for transparency and to allow deep background reading for those who want it.**

Longer summaries of parts of the dissertation are also available if you want a little more information:

[Summary of Chapters 1-4](DisSummary_Chapters1_2_3_4_How_Research_Done.md) for an understanding of the background and methodology

Two discovery studies provided the evidence that some help for tool design and acquisition might be needed. These are written up in the dissertation chapters 5 and 6. 

[Summary of Chapter 5](Dis_Chapter5_Experiences_with_Tools.md) for a description of the work on people's experiences of tools to support testing

[Summary of Chapter 6](Dis_Chapter6_Who_is_Testing.md) for a description of the work on the characteristis of people doing testing

The two discovery studies (Chapters 5 and 6) established that testing tools frequently fail the people using them, and that testers are a far more diverse group than stereotypes suggest. The next challenge was to turn those findings into something practically useful: a framework that could help tool designers and purchasers make better decisions. Dissertation chapters 7 and 8 describe how that framework — **idea-t** ("Influencing the Design, Evaluation and Acquisition of Tools for Testing") — was built.

[Summary of Chapters 7 and 8](Dis_Chapter7and8_building-idea-t.md) for a description of the process to build and prototype idea-t.

The idea-t framework was then evaluated and refined through a series of formative case studies, with the idea-t framework being improved as a result of the comments from the people who had used it. A sixth study was done - a retrospective analysis of customer issues with one particular commercial tool, to identify where the idea-t framework might have supported early decision making for the tool design, and which heuristics would have been most useful. This was followed by an expert review.

[Summary of Chapters 9, 10 and 11](Dis_Chapter9-10-11_Evaluating_idea-t.md) provides a summary of the chapters discussing the evaluations. More detailed summaries of the case studies also form part of the idea-t framework itself, and can be found in the ["How To" folder](../How-To/About-How-To-Folder.md) of the framework, under "Case Studies".

FInally, the dissertation has a discussion of the research as a whole piece of work, including applying the idea-t framework to itself, and comparing it with other frameworks.

[Summary of Chapters 12 and 13](Dis_Chapter12and13_Learnings.md) provides a summary of the discussion and conclusions of the dissertation.

The dissertation may be downloaded from the [University of Malta Open Access Repository OAR@UM as a PDF]( https://www.um.edu.mt/library/oar/handle/123456789/144337).

The precis and summaries were produced with the help of Claude *(Claude Sonnet 4.6, Anthropic, April 2026)*.

## Using Claude to Produce the Precis and Summaries for the Disseration.

No AI was used to write the original dissertation; it was written up by Isabel. 
These summaries produced by Clause and then edited by Isabel were the result of a set of instructions and conversation, working from a pdf of the dissertation as published, using Claude Sonnet 4.5. 
[This document with the transcript of the instructions and conversation with Claude](Claude-conversation-precis-dissertation.pdf) is attached for transparency.

</details>



[Back to Top](#TopofPage)
## About Us 

<details close>
<summary>About Isabel</summary>


### Isabel Evans - Researcher - my brief history

After more than 30 years in IT, on software industry projects, quality and testing practitioner I am now a part-time post-graduate student at the University of Malta. My research focuses on human factors in test automation. My interest in this topic arose from real-life experiences as a test manager, quality manager, and test consultant. I am an author, including a book, "Achieving Software Quality Through Teamwork", and chapters in "Agile Testing: How to Succeed in an eXtreme Testing Environment", "The Testing Practitioner", and "Foundations of Software Testing". I've spoken and told stories at software conferences worldwide, as well as chairing EuroSTAR (2019) and HUSTEF (2018). I am a Fellow of the British Computer Society and received the 2017 EuroSTAR Testing Excellence Award. Having graduated in March 2026, I am now Dr. Isabel Evans.

- [My linked-in profile](https://www.linkedin.com/in/isabelevans/)
- [My website](https://isabelevansuk.wordpress.com/)
- [My blog with consultancy stories](https://isabelevansconsultancy.wordpress.com/)
- [My other blog with stories about my interests](https://isabelevanswriting.wordpress.com/)

I do not use other social media. 


</details>


### Our Linked-in profiles:

[Isabel Evans](https://www.linkedin.com/in/isabelevans/)

[Prof. Chris Porter](https://www.linkedin.com/in/chrisporter/)

[Prof. Mark Micallef](https://www.linkedin.com/in/micallefmark/)

