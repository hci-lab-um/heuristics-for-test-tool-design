<a name="TopofPage"></a>
# Quality Attributes
[◄ Go back to Heuristics List in README file](README.md)

The purpose of this page is to help you prioritize which quality attributes are important for your tool, depending on your answers to the different heuristics. This is based on evidence in the research data. You can use the quotes and the data to help you build your requirements - in particular to strengthen your context description and personas.

Parts of this page:
- [List of Heuristics with Quality in Use and Product Attributes Associated](#List1)
- [What are Quality Attributes?](#WhatareQA1)   
- [Table 1: Quality in Use Attributes](#table1)   
- [Table 2: Product Quality Attributes](#table2)   
- [Building Quality Attribute Pyramids to get to the Desired UX](#pyramid1)  
- [More Information](#More) 

<a name="List1"></a>    [Back to Top](#TopofPage)

## List of Heuristics and Related Attributes 

<details close>
<summary>List of Heuristics and Related Attributes</summary>

| Heuristic | [Quality in Use](#table1) | [Product Quality Attributes](#table2) |
|-------------|-----------------------|----------------------------------------------------|
|H01. [Why do we need this tool?](H01-why-do-we-need-this-tool.md)| Freedom from Risk | User goals, Appropriateness|
|H02. [Who will use or be affected by the tool?](H02-Who-will-use-or-be-affected-by-this-tool.md)|Satisfaction|User goals, Appropriateness|
|H03. [What previous experiences do people bring to the tool?](H03-What-previous-experiences-do-people-bring-to-the-tool.md)|Effectiveness, Satisfaction| Learnability, Appropriateness, User error protection, Recognizability|
|H04. [What communication needs or preferences do those people have?](H04-What-communication-needs-or-preferences-do-those-people-have.md)|Effectiveness, Satisfaction, Flexibility | Learnability, Accessibility, Recognizability |
|H05. [What learning perspectives and goals do those people bring?](H05-What-learning-perspectives-and-goals-do-those-people-bring.md)|Effectiveness, Flexibility | Learnability, User error protection |
|H06. [What learning preferences do those people have?](H06-What-learning-preferences-do-those-people-have.md)|Effectiveness, Flexibility | Learnability, User error protection, Recognizability |
|H07. [Where will the tool be used?](H07-Where-will-the-tool-be-used.md)|Context coverage| Operability |
|H08. [What workflows will the tool be part of?](H08-What-workflows-will-the-tool-be-part-of.md)|Effectiveness, Context coverage|  Operability, User goals, , Appropriateness, Maintainability, Functionality, Security, Compatibility, Recognizability |
|H09. [What risks are associated with those workflows?](H09-What-risks-are-associated-with-those-workflows.md)|Freedom from Risk,  Context coverage| Operability, Appropriateness, Performance, Maintainability, Reliability|
|H10. [What work styles are acceptable in those workflows and teams?](H10-What-work-styles-are-acceptable-in-those-workflows-and-teams.md)|Context coverage and Flexibility, Satisfaction |Operability,  Accessibility, Maintainability, Security|
|H11. [When will the tool be used?](H11-When-will-the-tool-be-used.md)|Efficiency, Context coverage | Operability, Accessibility, Appropriateness, Performance, Maintainability, Compatibility, Reliability, Recognizability|
|H12. [How long will the tool be used?](H12-How-long-will-the-tool-be-used.md)| Context coverage | Portability|

</details>

<a name="WhatareQA1"></a>    [Back to Top](#TopofPage)

## What are Quality Attributes?

Quality attributes are properties of a product which affect how well the product performs. Generally, a software system but it could be some other product or service.  
Some of these are **Quality in Use** attributes: they refer to attributes that are a measure of how good the experience is when using the product. They include the effectiveness and efficiency with which someone can carry out their task, their safety, and the flexibility with which they can work. 
Others are technical or **Product attributes** which are built into the product and which the building blocks contributing to how the quality in use is achieved. They include functionality, usability, performance, security, and many others.  

 <a name="QARD1"></a>   
 
[Back to Top](#TopofPage)


### Quality Attributes in the Research Data

What makes a tool successful is definitely not just its functionality. Here’s some data and quotes from the research:

- 98% of the participants mentioned usability and quality in use of the tools as a concern, issue, or necessity. Over 40% of the comments were about usability. <br> *``I first had to define the fields (name, data type, etc.) Then somewhere else in the admin UI, I had to configure where this field would appear on the test case form for the project. Then somewhere else again in the admin UI, I had to define the set of possible values for the dropdown fields I’d added. [. . . ] infuriating (and requires a re-learn [of] this ridiculousness every few months when I get such admin requests).”*
- 91% of the participants mentioned other attributes including functionality, making up 34% of the comments. <br> *“every time I have to deal with a new tool, it’s the matter of installation that is the most difficult.''*

Table 1 lists the QiU attributes with a comment for each on sub attributes and some questions to ask yourself when designing the tool.

<details close>
<summary>Table 1: Quality in Use Attributes</summary>

<a name="table1"></a>    [Back to Top](#TopofPage) 

**Table 1: Quality in Use Attributes**

|Attribute         | Comment | Which heuristics are affected? |
|:-----------------|:--------|-------------------------------------------|
|Effectiveness     |When someone is carrying out a task, using the testing tool, how well does it support them to carry out the task confidently, so they know they have not made mistakes, and know they are achieving what they want to achieve, accurately and completely?| H03, H04, H05, H06, H08 |
|Efficiency        |When someone is carrying out a task, using the testing tool, how much effort does it take them to carry out the task?                  | H11 |
|Satisfaction      |Satisfaction is measured as a mix of a person's perception of the usefulness of the product, how much they trust it, the pleasure they get from using it, and the level of comfort they have. When you are designing the test tool, questions you might ask yourself include: <br> *When the person is using the software, how satisfied are they that the software contributes usefully to the task?* <br> *Do people trust the software to be producing accurate results?* <br>   *Does using the software give the person any pleasure?* <br>  *Is the person comfortable using the software?*   <br> Think about how you can provide testers with feedback within the tool that gives positive answers to these questions.  | H02, H03, H04, H10 |
|Freedom from risk | The testers and other stakeholders for the tool will face risks - domain, project, product, from the choice of using or not using the tool. This includes economic, health and safety, and environmental risks. Ask yourself, <br> *Will any stakeholder be more protected or less protected from economic damage?* <br>  *Will any stakeholder be more protected or less protected from damage to their health, safety, life?* <br>  *Will the environment (society, natural world, resource usage, sustainability be more protected or less protected by the use of this tool?* <br> Think about how the tool design will help to mitigate risk.|H01, H09 |
|Context coverage <br> and Flexibility |The tool will be used in a range of contexts - It may not be possible to understand all the contexts completely, your stakeholders may not remember to tell you about all the contexts, but we should make some attempt to understand the possibilities. We also need to understand what level of flexibility is needed in those contexts and for the people using the tool. Ask yourself: <br> *Given everything above, have we thought not just what was explicitly told us, but also asked "where else?" "when else?"* <br> *How much can someone adapt the software to be suitable for themselves?* <br> Think about accessibility needs, people adapting the tool to new contexts, people learning and gaining confidence to use the tool in different ways. Conversely you may want to reduce flexibility if the context has domain risks and restrictions. |H04, H05, H06, H07, H08, H09, H10, H11, H12|

</details>

Usability is a key contributor to QiU, and is multi-faceted. Breaking down the comments and concerns on usability we found that operability is the most important usability factor for our participants, followed by learnability, and being supported to meet their goals. 
Other attributes appeared less often. That doesn't make them less important - it just means that for our participants they are not currently their biggest concern.
The other attributes were mentioned often in the context of a problem that adversely affecting the overall user experience. 

In the table 2, the attributes are listed in order of frequency measured by how many people mentioned them, and how often.

Notice how low in the list functionality comes; people don't want more functionality; they want the overall experience to be better for the functionality supplied. 
Similarly, user interface aesthetics were mainly mentioned as an irritation sometimes disguising what became a poor overall experience.


<details close>
<summary>Table 2: Product Attributes that build to Quallity in Use</summary>
<a name="table2"></a>     [Back to Top](#TopofPage) 


**Table 2: Product Attributes that build to Quality in Use**

| Attribute       |  Notes | Which heuristics are affected? |
|:----------------|:------|--------------|
|Usability: Operability     | Operability is about how well the tool supports people to move through their workflows in use, once then have learned how to use the tool. Around half of all usability comments were about operability, in particular about tools being superficially easy to learn, or having an attractive interface, but then not supporting long term use through the activities over time. That could be improved by thinking in particular about how maintainability of the tests and test artefacts is needed. Additionally, some participants reported that security blockers meant that the tool looked like it would be useful, but they had no access to it - security blocked operability: <br> *“Trying to identify who had access, and what access they had [. . . ] I know how to do it (have learned earlier) but I am still not sure which of the local groups give access to what...''* <br> Operability is important for the effectiveness and efficiency of how people work, and is strongly supported by the other quality attributes. Workflow design is key to supporting operability.|H07, H08, H09, H10, H11 |
|Usability: Learnability    | Learnability is about how easy it to learn to use the tool, it is a pre-requisite for the tool being operable; if you cannot learn it, you cannot use it. About a quarter of usability comments were about the learnability of tools. Some workshop participants discussed a trade-off with some tools being harder to learn, but then more useful, and other tools being easy to learn, but then less powerful. Some management level participants talked about there being no time for training courses, and needing to acquire tools that needed minimal learning. We also found people had strong - and widely differing views - about the media, methods, and purposes of learning - these are reflected in the heuristics. <br> *“that I can quickly get to testing without having to waste time learning the tool, or how the tool wants me to do it”*| H03, H05, H06, H04|
|Usability: User Goals      | The tool needs to support people to meet their goals. Just under a third of participants talked about how well - or otherwise - their tools supported them to meet their goals: <br> *“(the best solution I have found) is a combo of (Tool 1) and (Tool 2), but neither does exactly what I want. Very frustrating. [. . . ] I don’t want to load each page manually and record the results in a spreadsheet so I can show change over time.”* |H01, H02, H08 |
|Portability      |	Portability was the most frequently mentioned quality attribute apart from usability; just over a quarter of points made were about the installability, adaptability and  of tools. Installation, set-up problems, uninstalling, and being able to change to a new tool were most mentioned by testers participating the surveys and workshops.<br> *“Getting the hang of it [. . . ]  processes [. . . ] found it was no longer supported . . . Aargh!”* *``For some reason, everybody who develops tools prepare YouTube video[s] about how to use the tool but not how to install it.”*| H12 |
|Maintainability  | Maintainability includes modularity, reusability, analysability, modifiability.  For test tools the design needs to take in account supporting the maintainability of the tests and test artefacts, as well as consideration of the maintainability of the tool itself. <br> *“running the tests is quite easy . . . The difficult part is maintaining the tests when it grows massively.”*| H11, H10, H08, H09|
|Security	      | Nearly a quarter of the participants had comments about security, access rights and the ability to get to the tool to use it. Security breaches were not mentioned so much; this is all about the aspect of security that provide tool and data access appropriate to the testers' types and levels of authorization, rather than blocking them. <br>One person referred to being *`stuck in limbo'* because they were unable to get access to the tool they were required to use, and in discussing these results with practitioners that problems has been recognized by others.| H08, H10|
|Compatibility	  | Around a quarter of participants reported concerns and requirements around co-existence and interoperability of the tool with other tools, and in multiple shared environments | H08, H11|
|Performance      |	Just under 10% of comments were about performance of the tool. Performance includes time behaviour, resource utilization and capacity. Resource utilization will be of interest for any stakeholders looking at economic or environment risk.|H09, H11 |
|Functionality    | Functionality - including the completeness, correctness, and appropriateness of the tool for its use - was lower on the list of people’s concerns than other attributes. Just under half of the participants mentioned it, but it wasn't what they talked about most.| H08|
|Reliability	  | About 10% of participants had requirements and concerns around reliability of the tools. Reliability includes the tool's availability, fault tolerance, and recoverability, while the maturity of the tool's software contributes to its reliability.|H09, H11|
|Accessibility   | Accessibility was mentioned by a small number of participants in terms of performing accessibility testing with specialist tools. However, a question not raised was the accessibility of test tools themselves. This was strongly discussed by expert accessibility reviewer. There are legal and moral implications around workplaces - including test teams - being open to a diverse group of people. | H04, H10, H11 |
|User interface aesthetics | The aesthetics of the user interface less mentioned, and then mainly as a source of irritation if a tool <br> *``looked good but didn't meet expectations.''* <br> The aesthetics is important to support the operability and accessibility of the tool, but is not as important as accessibility and support for learnability, operability and workflows.| H04|
| Appropriateness | A very small number of participants talked about tools not always being appropriate - for their planned purpose but in new context, for example. Two correspondents used the word *`magical'* to describe management expectations of automation. <br> *“supports your workflow vs forcing you to change. People [are greater than] process/tools”*|     H01, H02, H03, H08, H09, H11                                   |
|Recognizability | A very small number of participants talked about tools not always being recognizable for what their purpose was - the naming of a tool or sometimes where it was obtainable from sometimes masked the availability of a useful tool. For example, useful tools in private repositories:  <br> *"[the tool] was in a private GitHub repository"*                                     | H03, H04, H06, H08, H11|
|User error protection |Some participants talked about their fears when using the tools - of looking foolish, of losing data, of making mistakes. Protecting users against making mistakes increases their Effectiveness. <br> *“it is scary and I always get stuck. I am delaying the inevitable (frowny face).”* | H03, H05, H06 |

</details>

 <a name="pyramid1"></a>    [Back to Top](#TopofPage)

## Building Quality Attribute Pyramids to get to the Desired UX

<details close>
<summary>Quality Attribute Pyramids</summary>

Once you have a good understanding of *Who* is going to use the tool and *Why*, and their *Context*, you can start to prioritize the quality attributes and identify which technical attributes contribute to the QiU attributes.

For example, if this tool is to be used in a safety critical domain, to manage and report on critical tests, and will be used by people with a range of experiences and skills, you might focus on:
- health and safety as highest priority;
- effectiveness so that people using the tool are able to see they have taken the action they intended;
- built into enhanced operability but deliberately lowered flexibility of workflows;
- learnability supported by a range of learning materials and a training course;
- supported by high levels of reliability and security.

For example, if this tool is to be used in an organization that values a fast time to market, uses agile processes with high team autonomy, you might focus on:
- efficiency of the people using the tool to work at speed;
- flexibility of the workflows to allow teams to tailor workflows to their own needs;
- learnability supported by the tool interface and with a background of easy to access material;
- supported by performance to aid speed;
- supported by maintainability to support change.

</details>




<a name="More"></a>     [Back to Top](#TopofPage)

## More Information

- [Standards and Reference Texts](#Std1)   
- [Usability, Quality in Use, and the User Experience: how they relate together](#UI-LX1)   
- [How did the research reveal these figures?](#QARD2)
- [Our Academic Papers](#paper1)
  
<a name="Std1"></a>     [Back to Top](#TopofPage)

## Standards and Reference Texts

<details close>
<summary>Standards and References</summary>

[Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics)

[Summary of the ISO/IEC 25000 series of standards](https://iso25000.com/index.php/en/iso-25000-standards)

[ISO 25019 portal](https://www.iso.org/standard/78177.html)

NB: even as I write this, new standards are being developed, published, and discussed meaning there are several ways of dividing up the quality in use and product quality attributes. 
On this page, I have provided a simplified summary of some of the main quality attributes, plus notes from the research data. 
You can of course go to buy the new standard, [ISO 25019](https://www.iso.org/standard/78177.html) which has different definitions.
Or use this summary from TMAP of the previous version ISO 25010 with their additional definitions for AI and sustainability [Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics). 

</details>


<a name="UI-LX1"></a>    [Back to Top](#TopofPage)

## Usability, Quality in Use, and the User Experience: how they relate together

<details close>
<summary>Usability, Quality in Use, and the User Experience: how they relate together</summary>

Quality in Use (QiU) and Usability had the most frequent mentions in our data. 
Understanding how the different attributes are building blocks to the overall user experience (UX) helps us to design in a better UX, shown in the flowchart below. 
A good User Interface (UI) is supported by interaction design, and contributes to usability, which also includes designing for the users' efficiency, effectiveness, support to meet their goals in their context. 
Usability is one contributor to quality in use, which also includes flexibility in use and freedom from risk. 
QiU is also supported by all the technical attributes, such as maintainability, performance, security. 
QiU contributes to UX, and design should address trust, credibility, flow through tasks and the usefulness of the product. 
All of this, influenced by past experiences, mantal models and personal circumstances leads to the lived experience, and gives rise to emotions. 

![Flowchart showing the relationship between UI design, usability, quality in use, UX and the lived experience. ][ui-lxflow](UItoLX.jpg)

[ui-lxflow]: UItoLX.jpg

</details>




<a name="QARD2"></a>    [Back to Top](#TopofPage)

## How did the research reveal these figures?

<details close>
<summary>How the research reveal the figures?</summary>

The research to find these figures included several rounds of data collection and analysis, shown in the flowchart below.
Data was collected in interviews, workshops, and surveys with test practitioners. 
The data was analysed using a variety of qualitative and quantitative methods, and re-analysed by a second pair of researchers to check the results matched.
The analysis results were synthesised into a number of outputs, including this repository of heuristics. 
The heuristics have been evaluated in reviews with test, UX and accessibility experts.

![Flowchart showing the research activities to reach the figures in the tables. ][researchflow](r-flow.jpg)

[researchflow]: r-flow.jpg

</details>



<a name="paper1"></a>    [Back to Top](#TopofPage)

## Our Academic Papers
<details close>
<summary>Academic Papers</summary>

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Stuck in limbo with magical solutions: The testers’ lived experiences of tools and automation." In Proceedings of the 15th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, vol. 2, pp. 195-202. SCITEPRESS-Science and Technology Publications, 2020.

Evans, Isabel, Chris Porter, and Mark Micallef. "Scared, frustrated and quietly proud: Testers’ lived experience of tools and automation." In Proceedings of the 32nd European Conference on Cognitive Ergonomics, pp. 1-7. 2021.

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Test Tools: an illusion of usability?" In 2020 IEEE International Conference on Software Testing, Verification and Validation Workshops (ICSTW), pp. 392-397. IEEE, 2020.

</details>



