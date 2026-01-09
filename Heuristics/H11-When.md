

# Heuristic H11 When?

[◄ Go back to README](../README.md)

[◄ Back to About the Heuristics Page](About-Heuristics-Folder.md).

## Navigation hint (where you are in idea-t)

Theme Context?  

Keyword When?

Question: When will the tool be used?

## In brief:

This heuristic implies "how quickly?" and other time-related questions, as part of "when?"

- Level of urgency during the SDLC, speed a person can work with the tool (blockers, accessibility), staging of tasks in the workflow (learning and retaining knowledge).
- Time factors for the product under test, for the person using the tool, and within the tool and workflow might affect the tool design.


## Expanding this heuristic
<details close>
  <summary>Click for quick start summary
  </summary> 

some words of summary

</details>

<details close>
  <summary>Click for explanation of the heuristic
  </summary> 

Think about: 
  
- For the timescale of **product under test:** There may be a different urgency as deployment approaches, or when in support as a live product. The workflow may take place through different lifecycle stages of a product under test, and  therefore some activities’ urgency may change, risks may change, perceptions of quality may change. Defects may need to be managed differently in the early stages of a product lifecycle (during prototyping for example) compared with defect management during mainstream of product development. 

- For the **person using the tool:** Some people may require longer than others to complete what looks like the same workflow task: they might be working at a greater level of detail, they might be learning, they might be using assistive technology that changes the way they receive and impart information, they may be waiting on other activities. Organizations had expectations of how long tasks should take.
- Think about **how much** will the tool be used - by a person or by a team - will it be used enough to justify learning how to use it?

- Within the **tool and workflow:** The workflow may take an extended time, or be done in stages with time gaps.

- For the **tests and test artefacts**, how much and how quickly will they change over time?


</details>

<details close>
  
  <summary>Click for sub questions and alternative questions
  </summary> 

### Sub questions and alternative questions

Key questions to ask yourself:
- When during the product lifetime (PL) and during the software development lifecycle (SDLC) is the tool used?
- What urgency is there to the tasks the tool supports – and does that change across the SDLC and PL?
- Are there external time factors that affect time/dates?
- What time are people allowed by their organizations to complete their tasks, and how can the tool be designed to support that?
- Do some people need longer to complete tasks perhaps because of accessibility requirements and use of assistive technology to engage with the tool?
- Are tasks supported by the tool contiguous or broken with time gaps in the workflow?
- Do tasks need to be done repeatedly, perhaps updating an artefact without losing its history? How will you design in maintainability of the tests and related artefacts?
- Are there any situational impacts for different users e.g. a business tester might not be in an office - may be in a reactive or distracting environment, therefore doing this testing between other business tasks; the answer to 'When?' may be 'intermittantly in gaps between other tasks'.
- Will any of the tool users need to split tasks down either to complete them in intermittant bursts of work, or because an activity - for example running a test - may be started by one person and handed over to another person to complete it?
- When else will the tool be used or impact on people's work?
- Can we use the tool straightway or will it take time to implement the tool and train people?
- How long will it take to deploy?
- Is it a timely solution?
- When on-boarding new team members how much time will tool training require?
- How quickly will the tool supplier (vendor, open source team or in-house team) take to respond to questions? Is there a service level agreement for responding? Is there a clear communication path/responsibility that helps with response time and content? Is this both way (supplier to customer and customer to supplier)?
- Do all the stakeholders have the same perception of `urgent' and the same timescale for `urgent'?

  Participant quote: `` I don't care who controls (X) I just want it sorted out'' This is part of the user experience of the tool.




### Not? 
When won't the tool be used?
 

- maybe a list here

### Else?
When else might the tool be used?



</details>

## Examples

<details close>
  
  <summary>Click for evidence, case studies, usage cases and quotes from the research for this heuristic
  </summary> 
  
### Usage cases
<details close> <summary>Mini usage case</summary>
In one case study, the organization was working with SAAS software. They commented that although asking when during the SDLC the tool is used is a useful question, for their context a more useful question could be 
 <i>``Do some tasks need longer to complete (causing the tasks to be split up over a longer time period)?’’ </i>
 They said ``Tool is sometimes used for a specific project, after which usage drops or ends. ... mainly used for testing projects, as well as testing managed applications. As a SaaS tool, we keep developing in order for the application to stay relevant and prolong the tool’s life span indefinitely.''
 The way the tool is delivered changes the design decisions and which heuristics/questions are relevant. This affected how H11 and H12 were used in this orgaization.
  
</details>

### Case studies examples

### Quotes from research participants

Research Point: we found that participants were frustrated by tools slowing down their work. We found participants with accessibility requirements could be slowed or blocked by the test tool not playing well with the assistive technology. We found participants had different views on all these points, depending on the domains and work styles they had encountered.

*``initially easy to use but impossible to maintain''*

*``We decided it would be too much effort to implement and maintain alongside our ... gui tests''*

*``Easy: write test cases, create test cases, check results, update plans; Difficult: maintain test cases; copy and share test cases; share results of runs; modify test steps''*

*``...running the tests is quite easy. The difficult part is maintaining the tests when it grows massively''*

*``a decision reversed''* about implementing a requested tool and then a new one immediately being chosen by management...

</details>

## How to answer this heuristic

<details close>
  
  <summary>Click for activities and quality attributes that help answer this heuristic
  </summary> 
  
### Activities

To understand *When* the tool might be used, and other *time-related* factors, you can add time related information to the workflows you have already built in H08.



Other Activities:
- Revisit the Journey Maps and other activities from [H08](H08-Workflows.md) to add time factors.
- [PERT charting](https://www.smartdraw.com/pert-chart/examples/pert-chart-template/) can help us to understand workflow dependencies, whether activities can be done in parallel or must follow each other in series, where there is slack for  task to move, and where tasks are fixed on a critical path. NB: although this is a project management tool, used for planning, it is useful here as tool to understand how tasks are related to each other, and where they might be overlaps or waits between tasks. 


### Quality Attributes

- Quality in Use Attributes: Efficiency, Context coverage
- Product Quality Attributes: Operability, Accessibility, Appropriateness, Performance, Maintainability, Compatibility, Reliability, Recognizability

Mapping Heuristics to Quality Attributes is explained in the [Quality Attributes Folder](../How-To/QualityAttributes/About-Quality-Attributes-Folder.md)

We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help with context development. You may need to revisit your personas to strengthen them with localization points. Design a way for people to find the tool and its supporting training materials.They include time-related attributes such as efficiency of the person doing the work, and time-related performance of the software. Note that one of our participants - who is a screen reader user - also asked that for consideration of the additional time factors needed (a) if the tool does not behave well with a screen reader, and (b) when time boxes and constraints are put on staff to complete a task by the organization.**



</details>

## Navigation hint (where in idea-t to go next)

[◄ Back to README](../README.md)

[◄ Back to About the Heuristics Page](About-Heuristics-Folder.md).

[◄ To H01 Why?](../Heuristics/H01-Why.md)  if you have identified stakeholders who might have goals you have not yet considered. 

[◄ To H02 Who?](../Heuristics/H02-Who.md)  because in identifying contexts you might identify stakeholders you had not considered.

[◄ To H07 Where?](../Heuristics/H07-Where.md)  because you may now have identified other places the tool will be used.

[◄ To H12 How Long?](../Heuristics/H12-HowLong.md) because H12 is the next heuristic in the list, and is part of the "Context?" theme.
