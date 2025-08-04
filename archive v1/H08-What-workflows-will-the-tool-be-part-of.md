<a name="TopofPage"></a>
# H8 What workflows will the tool be part of?
[◄ Go back](README.md)

Theme: CONTEXT?

## Quick Start

- Heuristic Question: What workflows will the tool be part of?
- Workflows describe the steps people take to complete a series of tasks. Workflows include tasks supported by the tool, and also tasks upstream and downstream from the tool.
- Also ask what workflows or problems are we choosing NOT to support and why
- What changes would we need to make in our ways of working or processes to make the best use of the tool?
- Quality in Use Attributes: Effectiveness, Context coverage
- Product Quality Attributes: Operability, User goals, Appropriateness, Maintainability, Functionality, Security, Compatibility, Recognizability
- [Mapping Heuristics to Quality Attributes](Qualityattributesv2.md)

## Explanation and sub-questions

<details close><summary>Click for further explanation</summary> 

Workflows describe the steps people take to complete a series of tasks. Workflows describe the organizational/business tasks to be completed.
Think about: 
- Workflows transcend tools and individuals, weaving across and between teams and organizations. 
- Workflows include tasks that could be supported by a tool, and also tasks upstream and downstream from the tool.
- Workflows are described by experts in texts such as standards, syllabi, training courses, text books, blogs, etc. but those descriptions do not always reflect the reality of what people need to do.
- There will be an obvious set of activities within a workflow for an individual. The workflow will extend across a team, and to other teams within and possibly outside the organization. Workflows include information exchange and communication between people, data exchange between tools and systems, task handovers.
- Tool to tool workflows.
- Tool to person workflows.
- Person to tool workflows.
- Person to person worksflows.
- Consider consequential activities in the pipeline, whether the tool can work within the pipeline, how to get entry into the pipeline and how to get out of the pipeline and to the next activity.
- Consder also integrations between tools / databases / other technology as well as considering workflows.
- When discussing this include UXers (workflows are about people) and automators (workflows are about technology) - both are needed, and the communication between them.


Key questions to ask yourself:
- What choices about their work practices and workflow contributions should individuals and teams have?
- Does the proposed tool cover part of a workflow, the whole of a workflow, or across more than one workflow?
- How complex are the workflows and do they include complexity-multipliers such as [large datasets, waiting times, institutional complexity](https://www.nngroup.com/articles/complex-application-design-framework/)?
- What other workflows are impacted by the workflow where the tool is used?
- What else is happening in the workflow apart from testing activities?
  
</details>


<details close>
<summary>Research Points and Quotes</summary>

Research Point: We found that testers reported tools not supporting their workflow and feeling that unsuitable workflows had been imposed on their work. Workflows in tools did not always support preferred working practices, and sometimes were barriers to progress rather than enablers. Not having a choice can be a blocker, but sometimes it is essential.  

*"Some workflows are imposed as we don’t want the users to use their initiative and ‘improve’ the workflow but miss an important step (to someone else) they were unaware was important.  Other workflows do not follow preferred working practices due to technical/cost constraints. Workflow modelling is REALLY important in tool design and the workflows need to be modelled so that the tool designers are clear on what is optional and what is not, so that they can make compromises when implementing the workflow (e.g. based on tool costs, workflow time constraints, etc.)."* 

*``supports your workflow vs forcing you to change. People > process/tools''*

*``most test case management systems impose a workflow that forces testers to waste time creating fake artifacts for exploratory testing;[tool named] is a sinkhole for time & effort''*

*``Tooling that enforces strict linearity and workflows, where I require more freedom are limiting''*

*``Too many of the testing tools, particularly "test management" or "test case management" tools that I've seen try to dictate the whole workflow for using them. For example, you might have to create your test cases in advance, assign them, group them, etc., which makes it very difficult if you want a more dynamic approach.''*

*``we don't have a "this is how we always do it" mentality, we take each feature and decide how it makes the most sense to test it based on our context (complexity of the feature, experience and availability of team members, tools available, schedule, risk, etc.) We also don't tend to bucket our testing into things like "API testing", "UI testing", etc. because we've found that we get more value out of mixing approaches that have traditionally been over-segregated.''*


</details>

<details close><summary>Mini usage case - iterating between H08 Workflows, H02 Who? and H01 Why?</summary>

In one use of the heuristis, a participant indicated both that this question is essential, and also noted its link to H01 and H02, and to the context for the investigation.
*'This heuristic would be in the core when mapping the current state together with the key stakeholders. I would use a current state mapping exercise to explore this heuristic effectively to understand both the big picture and role specific workflows. At this stage, it's crucial to loop back to questions of "why," "who," and the broader context to understand relevant motivations and connections. A current state mapping exercise captures individual activities and identifies bottlenecks within the process.'*

</details>



## Activities, tools and techniques to help answer the questions

 [Back to Top](#TopofPage)

 <details close>
  <summary> Click for activities </summary>

To understand and describe a workflow, you need to know the activities to be done, how they link together, who takes part, how workflows link together.
The test workflow and the development workflow will interact, but so might other organizational workflows. As part of those interactions, tools will need to interact.


We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help with context development. You may need to revisit your personas to think about which workflows they are involved in.**


The activities to understand this heuristic mean working with stakeholders and typical users for the tool. Workflow mapping and journey mapping are typical activities. In case you are not familiar with them, there are some external articles linked to below:
- Make a workflow diagram as a flowchart or a [wireflow diagram](https://www.nngroup.com/articles/wireflows/)
- As testing activities are complex and iterative, consider [designing for a complex workflow with interruptions](https://www.nngroup.com/articles/designing-for-waits-and-interruptions/)
- [Journey Mapping](https://www.nngroup.com/articles/journey-mapping-101/) including [experience maps, customer journey maps and empathy maps](https://www.nngroup.com/articles/ux-mapping-cheat-sheet/)
- [Service blueprint](https://www.nngroup.com/articles/service-blueprints-definition/) to get the interaction between the customer journey, the workflow and the technical flow
- Ask ["How might we? questions"](https://www.nngroup.com/articles/how-might-we-questions/) to look for options.

</details>

 [Back to Top](#TopofPage)
