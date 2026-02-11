<a name="TopofPage"></a>
# About the Research and the Researchers
[◄ Go to ReadMe](../README.md)

This page is about the research behind the heuristics, information about the researchers, and also has links to videos, academic papers and other resources.

## Presentation slides, videos and articles about the Research
<details openclose>
<summary>Click for Presentations, Videos and Articles</summary>

Podcasts:
- [Chat with Richard Seidl about stereotyping](https://www.youtube.com/watch?v=fn3Q3Gex_dE)
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
After nearly four decades working in the IT industry, mainly in software testing, latterly as a consultant and trainer, Isabel had observed that teams and organizations didn’t have the successes they anticipated with adoption of tools to support testing. Wanting to understand the blockers to test tool adoption and what might overcome these, with an initial idea that improving the usability of tools would help people adopt them and use them successfully, she started a post-graduate study at University of Malta to give a structure for researching the ideas. Isabel is working with Prof. Chris Porter and Prof. Mark Micallef who are her academic supervisors.

</details>


[Preprints of published papers are listed here](preprints.md) and a summary of the research journey story so far is below. 

<details close>
<summary>Click for Story So Far</summary>

###	Story So Far

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

**Evaluating the Heuristics - expert reviews:** We have taken versions of the heuristics to test experts and practitioners to understand if the content of the heuristics indicate anything useful about the people who will use the test tools. That includes asking someone who had built a tool whether the heuristics would have changed their thinking when designing/building the tool, and a review with an accessibility expert.
We updated the heuristics based on the review comments, in an iterative process.

**Evaluating the Heuristics - case studies:** We undertook an iterative build-review-refining of the heuristic set content through industry case studies to evaluate the heuristics in use.
The case study results were used to refine the heuristics based on comments and observations of them in use.
This GitHub repository is here to support the case studies and capture the heuristics and supporting information.


</details>

[Back to Top](#TopofPage)
## About Us 

<details close>
<summary>About Isabel</summary>


### Isabel Evans - Researcher - my brief history

After more than 30 years in IT, on software industry projects, quality and testing practitioner I am now a part-time post-graduate student at the University of Malta. My research focuses on human factors in test automation. My interest in this topic arose from real-life experiences as a test manager, quality manager, and test consultant. I am an author, including a book, "Achieving Software Quality Through Teamwork", and chapters in "Agile Testing: How to Succeed in an eXtreme Testing Environment", "The Testing Practitioner", and "Foundations of Software Testing". I've spoken and told stories at software conferences worldwide, as well as chairing EuroSTAR (2019) and HUSTEF (2018). I am a Fellow of the British Computer Society and received the 2017 EuroSTAR Testing Excellence Award.

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

