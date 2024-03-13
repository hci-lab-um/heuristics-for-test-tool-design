# Quality Attributes

## What are quality attributes?
Quality attributes are properties of a product which affect how well the product performs. Generally a software system but it could be some other product or service.  
Some of these are Quality in Use Attributes: they refer to attributes that are a measure of how good the experience is of using the product. They include the effectiveness with which someone can carry out their task, their safety, the flexibility with which they can work. 
Others are technical or product attributes which are built into the product and which the building blocks contributing to how the quality in use is achieved. They include functionality, usability, performance, security, and many others.  

NB: even as I write this, new standards are being developed, published, and discussed meaning there are several ways of dividing up the quality in use and product quality attributes. 
On this page, I am going to provide a simplified summary of some of the main quality attributes, plus notes from the research data. 
You can of course go to buy the new standard, [ISO 25019](https://www.iso.org/standard/78177.html) which has different definitions.
Or use this summary from TMAP of the previous version ISO 25010 with their additional definitions have added for AI and sustainability [Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics). 

## Quality Attributes in the research data
What makes a tool successful is definitely not just its functionality and technical attributes. Here’s some data from the research, also summarised in Table 1:

- 98% of the participants mentioned usability and quality in use of the tools as a concern, issue, or necessity.
- 90% of the participants mentioned management and organizational issues as a concern, issue, and support being necessary.
- 91% of the participants mentioned other attributes including functionality.

**Table 1: Themes: Organisational, Technical, Usability**
|Theme                        |	Participants   | Frequency |
|:----------------------------|:--------------:|:---------:|
| Organisational Management   |101 (90.9%)     |377 (27.8%)|
| Technical Attributes        |102 (91.8%)     |466 (34.4%)|
| Quality in Use / Usability  |109 (98.2%)     |563 (41.6% |

## Usability, Quality in Use, and the User Experience

Quality in Use (QiU) and Usability had the most frequent mentions in our data. 
Understanding how the different attributes are building blocks to the overall user experience (UX) helps us to design in a better UX, shown in the flowchart below. 
A good User Interface (UI) is supported by interaction design, and contributes to usability, which also includes designing for the users' efficiency, effectiveness, support to meet their goals in their context. 
Usability is one contributor to quality in use, which also includes flexibility in use and freedom from risk. 
QiU is also supported by all the technical attributes, such as maintainability, performance, security. 
QiU contributes to UX, and design should address trust, credibility, flow through tasks and the usefulness of the product. 
All of this, influenced by past experiences, mantal models and personal circumstances leads to the lived experience, and gives rise to emotions. 

![Flowchart showing the relationship between UI design, usability, quality in use, UX and the lived experience. ][ui-lxflow](UItoLX.jpg)

[ui-lxflow]: UItoLX.jpg

Table 2 lists the QiU attributes with a comment for reach on sub attributes and some questions to ask yourself when designing the tool.

**Table 2: Quality in Use Attributes**
|Attribute         | Comment |
|:-----------------|:--------|
|Effectiveness     |When someone is carrying out a task, using the testing tool, how well does it support them to carry out the task confidently, so they know they have not made mistakes, and know they are achieving what they want to achieve, accurately and completely?|
|Efficiency        |When someone is carrying out a task, using the testing tool, how much effort does it take them to carry out the task?                  |
|Satisfaction      |Satisfaction is measured as a mix of a person's perception of the usefulness of the product, how much they trust it, the pleasure they get from using it, and the level of comfort they have. When you are designing the test tool, questions you might ask yourself include: <br> *When the person is using the software, how satisfied are they that the software contributes usefully to the task?* <br> *Do people trust the software to be producing accurate results?* <br>   *Does using the software give the person any pleasure?* <br>  *Is the person comfortable using the software?*   <br> Think about how you can provide testers with feedback within the tool that gives positive answers to these questions. |
|Freedom from risk | The testers and other stakeholders for the tool will face risks - domain, project, product, from the choice of using or not using the tool. This includes economic, health and safety, and environmental risks. Ask yourself, <br> *Will any stakeholder be more protected or less protected from economic damage?* <br>  *Will any stakeholder be more protected or less protected from damage to their health, safety, life?* <br>  *Will the environment (society, natural world, resource usage, sustainability be more protected or less protected by the use of this tool?* <br> Think about how the tool design will help to mitigate risk.|
|Context coverage  |The tool will be used in a range of contexts - It may not be possible to understand all the contexts completely, your stakeholders may not remember to tell you about all the contexts, but we should make some attempt to understand the possibilities. We also need to understand what level of flexibility is needed in those contexts and for the people using the tool. Ask yourself: <br> *Given everything above, have we thought not just what was explicitly told us, but also asked "where else?" "when else?"* <br> *How much can someone adapt the software to be suitable for themselves?* <br> Think about accessibility needs, people adapting the tool to new contexts, people learning and gaining confidence to use the tool in different ways. Conversely you may want to reduce flexibility if the context has domain risks and restrictions. |

Usability is a key contributor to QiU, and is multi-faceted. Breaking down the comments and concerns on usability we found that Operability is important to our participants, followed by learnability, being supported to meet their goals. Other attributes appeared less often. In the table below, you can see the usability sub attributes in order of their importance to our participants, together with a comment on design points:

**Table 3: Usability sub attributes**
| Attribute       |  Notes | 
|:----------------|:------|
|  Usability      | Over a third of all comments mention usability in a generic way. Usability contributes to the QiU attributes of effectiveness, efficiency, and satisfaction. To really understand it we need to break it down into its sub attributes, in the rest of the table below. |
| Operability     | Operability is about how well the tool supports people to move through their workflows in use, once then have learned how to use the tool. Around half of all usability comments were about operability, in particular about tools being superficially easy to learn, or having an attractive interface, but then not supporting long term use through the activities over time. That could be improved by thinking in particular about how maintainability of the tests and test artefacts is needed. Additionally, some participants reported that security blockers meant that the tool looked like it would be useful, but they had no access to it - security blocked operability. Operability is important for the effectiveness and efficiency of how people work, and is strongly supported by the other quality attributes. Workflow design is kep to supporting operability.|
| Learnability    | Learnability is about how easy it to learn to use the tool, it is a pre-requisite for the tool being operable; if you cannot learn it, you cannot use it. About a quarter of usability comments were about the learnability of tools. Some workshop participants discussed a trade-off with some tools being harder to learn, but then more useful, and other tools being easy to learn, but then less powerful. Some management level participants talked about there being no time for training courses, and needing to acquire tools that needed minimal learning. We also found people had strong - and widely differing views - about the media, methods, and purposes of learning - these are reflected in the heuristics.|
| User Goals      | The tool needs to support people to meet their goals. Just under a third of participants talked about how well - or otherwise - their tools supported them to meet their goals. |
| User interface aesthetics | The aesthetics of the user interface less mentioned, and then mainly as a source of irritation if a tool ``looked good but didn't meet expecctations. The aesthetics is imporant to support the operability and accessiblity of the tool.|                         | 
| Context         |  under 20% of participants TBD |
| Satisfaction    |  just over 10% of participants TBD | 
| Accessibility   | Accessibility was mentioned by a small number of partiicipants in terms of performing accessibility testsiing with specialist tools. However, a question not raised was the accessiblity of test tools themselves. This was strongly discussed by expert accessiblity reviewer. There are legal and moral implications about work places - including test teams - being open to a diverse group of people. |
| Appropriateness | A very small number of particpants talked about tools not always being appropriate - for their planned purpose but in new context, for example. |                                        
| Recognizability | A very small number of participants talked about tools not always being recognizable for what their purpose was - the naming of a tool or sometimes wher it was obtainable from sometimes masksed the availability of a useful tool. For example, useful tools in provate repositories.                                       
| User error protection |Some participants talked about their fears when using the tools - of looking foolish, of loosing data, of making mistakes. Protechting users against making mistakes increases their Effectiveness.|



## Technical Quality Attributes
The technical attributes were mentioned often in the context of a problem that adversely affecting the overall user experience. The breakdown of technical attribute mentions in the data is in table 4. You can see that the attributes are in order of frequency, and the percentage given of the total number of technical comments and the percentage of all comments. Notice how low in the list functionality comes; people don't want more functionality; they want the overall experience to be better for the functionality supplied.

**Table 4: Technical Attributes Mentioned**
| Attribute       |  Notes | 
|:----------------|:-------|
|portability      |	Portability was the most frequently mentioned quality attribute apart from usability; just over a quarter of points made were about the installability, adaptability and  of tools. Installation and set-up problems, and being able to change to a new tool - for example uninstalling without knock-on problems was most mentioned by testers participating the surveys and workshops. |
|performance      |	Just under 10% of comments were about perforamnce of the tool. Performance includes time behaviour, resource utilization and capacity. Resource utilization will be of interest for any stakeholders looking at econmic or environment risk.|
|maintainability  | Maintainability includes modularity, reusability, analysability, modifiability.  For test tools the design needs to take in account supporting the maintainability of the tests and test artefacts, as well as consideration of the maintainability of the tool itself.|
|functionality    | Functionality - including the completeness, correctness and appropriateness of the tool for its use - was lower on the list of pepeople's concerns than other attributes. Just under half of the participants mentioned it, but it wasn't what they talked about most.|
| security	      | Nearly a quarter of the participants had comments about security, access rights and the ability to get to the tool to use it. Security breaches were not mentioned so much; this is all about the aspect of security that provide tool and data access appropriate to the testers' types and levels of authorization, rather than blocking them.|
|compatibility	  | Around a quarter of participants reported concerns and requirements around co-existence and interoperability of the tool with other tools, and in multiple shared environments |
|reliability	  | About 10% of participants had requirements and concerns around reliability of the tools. Reliability includes the tool's availability, fault tolerance, and recoverability, while the maturity of the tool's software contributes to its reliability.|
  
## Building Quality Attribute Pyramids to get to the Desired UX

Once you have a good understanding of *Who* is going to use the tool and *Why*, and their *Context*, you can start to prioritize the quality attributes and identify which technical attributes contribute to the QiU attrbutes.

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




## Standards and Reference Texts

[Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics)

[Summary of the ISO/IEC 25000 series of standards](https://iso25000.com/index.php/en/iso-25000-standards)

[ISO 25019 portal](https://www.iso.org/standard/78177.html)

## Our Academic Papers

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Stuck in limbo with magical solutions: The testers’ lived experiences of tools and automation." In Proceedings of the 15th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, vol. 2, pp. 195-202. SCITEPRESS-Science and Technology Publications, 2020.

Evans, Isabel, Chris Porter, and Mark Micallef. "Scared, frustrated and quietly proud: Testers’ lived experience of tools and automation." In Proceedings of the 32nd European Conference on Cognitive Ergonomics, pp. 1-7. 2021.

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Test Tools: an illusion of usability?" In 2020 IEEE International Conference on Software Testing, Verification and Validation Workshops (ICSTW), pp. 392-397. IEEE, 2020.

## How did the research reveal these figures?
The research to find these figures included several rounds of data collection and analysis, shown in the flowchart below.
Data was collected in interviews, workshops, and surveys with test practitioners. 
The data was analysed using a variety of qualitative and quantitative methods, and re-analysed by a second pair of researchers to check the results matched.
The analysis results were synthesised into a number of outputs, including this repository of heuristics. 
The heuristics have been evaluated in reviews with test, UX and accessiblity experts.


![Flowchart showing the research activities to reach the figures in the tables. ][researchflow](r-flow.jpg)

[researchflow]: r-flow.jpg
