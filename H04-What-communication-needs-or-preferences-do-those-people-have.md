<a name="TopofPage"></a>
# H4 What communication needs or preferences do people have?
[◄ Go back](README.md)

Theme: WHO?

## Quick Start:

- Heuristic Question: What communication needs or preferences do those people have?
- People have different communication styles. Media, speed, level of detail, accessibility needs, and so on change how people want to receive and impart information.
- Different stakeholders will have different requirements from the tool, and about the tool.
- This heuristic is used to add depth to your findings from H02 and H03. 	
- Quality in Use Attributes: Effectiveness, Satisfaction, Flexibility
- Product Quality Attributes: Learnability, Accessibility, Rcognizability
- [Mapping Heuristics to Quality Attributes](Qualityattributesv2.md)

## Explanation and sub-questions

<details close><summary>Click for further explanation</summary> 
 
Different people have different communication styles. The media, speed, level of detail, and other factors change how people want to receive and impart information. Some people have specific accessibility requirements. This is not a binary choice – generally people will fall somewhere on a spectrum for all of these factors, and also their preferences and needs may change in different situations and over time.

Think about:
- Providing choices in level of detail versus overviews, potentially from corporate to management to team and technical levels; the tool may not be directly used, but the data and information flows will be used across organizational levels.
- How communication styles may change (summary versus detailed, direct versus indirect).
- Providing multiple routes, methods and media for information and data sharing.
- Reducing the need to duplicate data (and hence updating) by automating data transfer across tool sets.
- Which senses people could use to interact with the tool. This includes both enriching the experience and also improving accessibility.
- Design choices that widen the tool's capability of being used across communication needs.
- Vendor and supplier communications: do they meet the needs of your stakeholders and you?
- How information about the tool is best shared to the community who will use it: they may have differing needs and communication styles.

Key questions to ask yourself:
- have you considered what type of communication people may require depending on their role, their place in the workflow, accessibility needs, persona preferences, level of detail needed, types of decision they are making?
- what level of detail are the people comfortable with and does that change with event, or role? 
- do people need to move between detail and overview?
- how do people prefer to receive and to provide information (e.g. pace of information delivery, e.g. preferred media, e.g. focus on outcome versus focused on people)?
- what different media are required to maximise accessibility?
- what situational differences may the people using the tool experience - for example testing may not be their full time role. They may be testing between jobs in an office, in a warehouse, in a hospital - these are all real example we came across when developing the heuristics. The testers may need to start and stop testing as they are interrupted by higher priority tasks (their "real work") and may need share a set of tests between them as they move between tasks as a team.
- what else may affect people's communication? Think about situational, temporary or permanent inhibitors or enhancers of communication in the situation in which people encounter the tool?
- How to communicate information about the tool to people who need to know about it, for example stakeholders: one participant needed to think about ``how to convince them the tool is needed and is the right choice?''


To understand *Who communicates how* you need to understand people’s characteristics, particularly their preferred communication styles. Use the answer to this heuristic question to help you further enrich your personas and your understanding of your stakeholders.

You will need to either understand the specific communication preferences of your specific users, or make generalized personas based on a communication model, for example the DISC profiles.  This is affected by people role/work persona – their behavior in work, rather than their personality. You can add this to your personas for the tool (see [Activities](#Activities-tools-and-techniques-to-help-answer-the-questions) below).

The DISC profiling method identifies communication styles in four quadrants: Dominance, Influence, Steadiness and Compliance. Each one indicates a pace of communication and how people oriented or otherwise.
We are all a mix of these.
- "D" is fast moving and results driven - dashboard?
- "I" is outgoing, people oriented - DM, interactive, group tool?
- "S" likes structure, consistency and a steady pace - form based tool?
- "C" likes facts, data, precision, order - spreadsheet?

People are divided among these profiles. Looking at people's hobbies as a proxy for their communication styles we found a wide mix of people testing: team and solo, practical and analytical, reserved and communicative. 
You could use the DISC to provide a set of communication characteristics towards your personas.

You also must consider accessibility needs and how those affect the choice of media, input and output options, etc.  You can use the accessibility analysis as a way to improve the communication through the tool for everyone. Accessibility needs may be permanent, situational or temporary. Accessibility needs may be based on sensory, physical, cognitive and emotional states.
</details> 


<details close>
<summary>Research Points and Quotes</summary>

Research Point: we found that people using test tools have a wide variety of communication styles and preferences. For example, 
- people with more experience and expertise used visualisation, with visual representations of information and concepts than less experienced people (this fits with work done by other researchers on other IT roles).
- people varied in whether they wanted details or summaries/overviews of data, and this did not fit to experience level.
- people varied in how much they wanted to work alone and how much with others.
Look at the different communication styles coming out in answer to a question about what activities they do in their role:

*``I am the listening ear for some people in the team. No role, not official. People need to talk to someone that is listening and if they want come with advice.  I make time for people.''*

*``I pair and ensemble a lot. ... I build networks of communication, facilitate peer to peer learning by introducing people and hold spaces where people share their work. I do a lot of exploratory testing and automate while exploring. I manage expectations of management, and optimize schedules.''*

*``Always communication. It is everywhere and above all. I am trying to organize everything, to keep track of everything (and getting pissed off silently (mostly) when important things are left somewhere in the air. Writing down ideas, good practices, even phrases.''*

*``Actual testing and I really avoid all the commercial stuff, working on bids, trying to win contracts with big clients, that sort of rubbish. I attempt to focus on the professionals that we employ, the people.''*

*``Manual testing, test automation, maintaining and improving CI, keeping pipelines green, creating of a testing framework, test case management.''*

*``It’s been… there’s no source of truth – if you want to know how projects are doing you have to look in 4 or 5 places''*

</details>

<details close> <summary>Mini use case: preferred tools leading to duplicated data and effort</summary>

One participant noted that communication preferences means choosing different tools with different interaction and interface styles. This can lead to duplication of effort and data: *'engineers want to know why do we have to go to another tool … they want to everything in the IDE; why should they need to also add info in confluence for example?'* Their example is GitHub and Confluence which required duplication of the same content for two different types of readers: *'Technical readers go to GitHub to read code and markdown, non technical stakeholders go to confluence pages to read detail ... An ideal would be to have a way that entries in GitHub markup could be transferred across to normal language in Confluence: automatically create confluence pages from GitHub markdown ... But to avoid gaps and differences over time, you want GitHub markdown to automatically go into Confluence, keeping the same content aligned.'*

</details>




<details close>
<summary>Mini usage case - communication is affected by context</summary>

When will the tool be used? For one organization we spoke with, this was particularly interesting - testing took place not just in the office, but in noisy and stressful work environments, and tests could be started by one person and completed by another becuase of work interruptions, sickness, and other factors.  We found examples of testers whose main job was as medical staff in a hospital or operatives in a warehouse: as business testers they still needed to use the test tool, but were not in the test lab.

</details>

### Accessibility

Disabilities can be permanent, temporary or situational. They can be physical, cognitive, learning, neurological, apply to any of the senses.
International and government bodies have standards, laws, guidelines and guidance materials.
You will find links to some Guidelines in the Activities below.


## Activities, tools and techniques to help answer the questions

 [Back to Top](#TopofPage)

<details close>
  <summary> Click for activities </summary>


There is a persona [worked example here in this repository](Technique-Personas-and-Archetypes.md) including communication preferences.

We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help with persona development.**

To help you with these activities here are links to some external sites with "how to" information: 
- Look at the [DISC profile communication preferences](https://tonyrobbins.com/disc/) either to inform personas, or to carry out DISC profiling - not to run a profile on everyone, but to think about the different communication needs and preferences shown in that model;
- Use the [Microsoft Inclusive Design Methodology](https://inclusive.microsoft.design/) to guide your design process by following their [Inclusive 101 guidebook](https://inclusive.microsoft.design/tools-and-activities/Inclusive101Guidebook.pdf);
- A fun workshop developed by the [Accessible Reality](http://accessible-reality.org/) team supported by the University of Dundee is the “Pirates” workshop which helps you think about the different types of access needs that a person may have.

  </details>
  
 [Back to Top](#TopofPage)
