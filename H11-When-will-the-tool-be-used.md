<a name="TopofPage"></a>
# H11 When will the tool be used?
[◄ Go back](README.md)

Theme: CONTEXT?

Heuristic Question: When will the tool be used?

## Explanation and sub-questions
Time factors for the product under test, for the person using the tool, and within the tool and workflow might affect the tool design.
This heuristic implies "how long?" and "how quickly?" and other time-related questions, as part of "when?"

Think about: 
  
- For the timescale of **product under test:** There may be a different urgency as deployment approaches, or when in support as a live product. The workflow may take place through different lifecycle stages of a product under test, and  therefore some activities’ urgency may change, risks may change, perceptions of quality may change. Defects may need to be managed differently in the early stages of a product lifecycle (during prototyping for example) compared with defect management during mainstream of product development. 

- For the **person using the tool:** Some people may require longer than others to complete what looks like the same workflow task: they might be working at a greater level of detail, they might be learning, they might be using assistive technology that changes the way they receive and impart information, they may be waiting on other activities. Organizations had expectations of how long tasks should take.

- Within the **tool and workflow:** The workflow may take an extended time, or be done in stages with time gaps.

- For the **tests and test artefacts**, how much and how quickly will they change over time?

Research Point: we found that participants were frustrated by tools slowing down their work. We found participants with accessibility requirements could be slowed or blocked by the test tool not playing well with the assistive technology. We found participants had different views on all these points, depending on the domains and work styles they had encountered.

*``initially easy to use but impossible to maintain''*

*``We decided it would be too much effort to implement and maintain alongside our ... gui tests''*

*``Easy: write test cases, create test cases, check results, update plans; Difficult: maintain test cases; copy and share test cases; share results of runs; modify test steps''*

*``...running the tests is quite easy. The difficult part is maintaining the tests when it grows massively''*

*``a decision reversed''* about implementing a requested tool and then a new one immediately being chosen by management...

Key questions to ask yourself:
- When during the product lifetime (PL) and during the software development lifecycle (SDLC) is the tool used?
- What urgency is there to the tasks the tool supports – and does that change across the SDLC and PL?
- Are there external time factors that affect time/dates?
- What time are people allowed by their organizations to complete their tasks, and how can the tool be designed to support that?
- Do some people need longer to complete tasks perhaps because of accessibility requirements and use of assistive technology to engage with the tool?
- Are tasks supported by the tool contiguous or broken with time gaps in the workflow?
- Do tasks need to be done repeatedly, perhaps updating an artefact without losing its history? How will you design in maintainability of the tests and related artefacts?
- Are there any situational impacts for different users e.g. a business tester might not be in an office - may be in a reactive or distracting environment, therefore doing this testing between other business tasks - the answer to `When?' may be `intermittantly in gaps between other tasks'.

## Activities, tools and techniques to help answer the questions

 [Back to Top](#TopofPage)

To understand *When* the tool might be used, and other *time-related* factors, you can add time related information to the workflows you have already built in H08.

We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These include time related attributes such as efficiency of the person doing the work, and time related performance of the software. Note that one of our participants - who is a screen reader user - also asked that for consideration of the additional time factors needed (a) if the tool does not behave well with a screen reader, and (b) when time boxes and constraints are put on staff to complete a task by the organization.**


Other Activities:
- Revisit the Journey Maps and other activities from [H08](H08-What-workflows-will-the-tool-be-part-of.md) to add time factors.
- [PERT charting](https://www.smartdraw.com/pert-chart/examples/pert-chart-template/) can help us to understand workflow dependencies, whether activities can be done in parallel or must follow each other in series, where there is slack for  task to move, and where tasks are fixed on a critical path. NB: although this is a project management tool, used for planning, it is useful here as tool to understand how tasks are related to each other, and where they might be overlaps or waits between tasks. 

 [Back to Top](#TopofPage)
