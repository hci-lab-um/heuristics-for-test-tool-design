# 12 heuristic questions to provoke thought and ideas when designing or choosing a test tool (quick start).  

On each heuristic below, the "about" link on each heuristic question takes you to additional information including explanations, sub-questions, usage scenarios. The quality in use and product quality attributes are attributes that of the tool that you may need to consider, and "[Mapping Heuristics to Quality Attributes"](Qualityattributesv2.md) takes you to more information about those attributes.

You might find it useful to start a list, mindmap, or postits grouping to help you. Start with the heuristic questions, add your own questions and relevant details from the explanation pages, as you think and discuss.

Expect this to be iterative. When you know more about Who? (Heuristics H02 - H06) you may find that feeds back to a better understanding of H01 Why? When you know more about Context? (Heuristics H07 - H12) you may find that feeds back to enriching H01 and H02-H06. 

## H01: Why?	

Why the tool is needed, what goals it supports, and what goals it doesn't support. What problem the tool is intended to solve, and if a tool is the best option for solving the problem.

- [About H01. Why do we need this tool?](H01-Why-do-we-need-this-tool.md)
- Key points: We found nearly a third of comments made about challenges with implementing tools successfully were management and organizational in origin, and were often about conflicting goals across the organization. A mutual understanding across stakeholders of why the tool is needed, what goals it supports, and importantly what goals it doesn't - or cannot - support is vital.
- Quality in Use Attributes: Freedom from Risk.
- Product Quality Attributes: User goals, Appropriateness.
  
## H02: Who? 

Who (else) will use the tool? Who provides information for inputs? Who uses information from outputs?	

- [About H02. Who will use or be affected by the tool?](H02-Who-will-use-or-be-affected-by-this-tool.md)
- Key points: We found a broad and non-stereotypical group of people are testing, and therefore may be using the tool. You will also have stakeholders who may not use the tool, but may influence the goals for the tool. As you identify Why the tool is needed, you might find that different stakeholders have different perceptions of why the tool is required and what it should do: you need to understand Who needs the tool.
- Heuristics H03, H04, H05, H06 will give you more information about "who?" 
- Quality in Use Attributes: Satisfaction.
- Product Quality Attributes: User goals, Appropriateness.

## H03: Experience? 

What previous experiences, expectations and skill levels do people bring? Testers do not conform to IT worker stereotype in their experiences.	

- [About H03. What previous experiences do people bring to the tool?](H03-What-previous-experiences-do-people-bring-to-the-tool.md)
- Key points: Thinking about previous experiences will help you focus on understanding expectations and skill levels, as well as communication styles. We found that testers do not conform to IT worker stereotypes in their experiences: we found boat builders, historians, philosophers, artists, musicians, urban planners and many other backgrounds. Different people will have different skills in technology, the specific tool set, testing, and the domain for the product under test.
- Quality in Use Attributes: Effectiveness, Satisfaction.
- Product Quality Attributes: Learnability, Appropriateness, User error protection, Recognizability.


## H04: Communication needs?	

People have different communication styles. Media, speed, level of detail, accessibility needs, and so on change how people want to receive and impart information.	

- [About H04. What communication needs or preferences do people have?](H04-What-communication-needs-or-preferences-do-those-people-have.md)
- Key points: Providing choices in level of detail versus overviews, potentially from corporate to management to team and technical levels; the tool may not be directly used, but the data and information flows will be used across organizational levels. Providing multiple routes, methods and media for information and data sharing. Reducing the need to duplicate data (and hence updating). Think about which senses people could use to interact with the tool, enriching the experience and improving accessibility. Make design choices that widen the tool's capability of being used across communication needs.
- Quality in Use Attributes: Effectiveness, Satisfaction, Flexibility.
- Product Quality Attributes: Learnability, Accessibility, Recognizability.

## H05: Mastery or Task learning? 	

People may want to master the tool/become expert or just to learn enough to enable them to complete a specific task. Consider both by personal choice and organizational pressure.	

- [About H05. Do people want "tool mastery" or "task completion"?](H05-personal-learning-goal-mastery-or-task-based.md)
- Key points: The learning goal has impact on long and short term goals, on investment versus cost viewpoints. If just achieving the next task is the goal, then short bursts of 2 minute videos might be a good way to deliver information about the tool, or provision of wizards to step through tasks. Learning for mastery might require longer blocks of dedicated time, information about underlying principles, and practice sessions.
- Quality in Use Attributes: Effectiveness, Flexibility.
- Product Quality Attributes: Learnability, User error protection.

## H06: Learning preferences?	

Solo, pair or group learning? Video, audio, text, diagrams? Online or face to face? Guided or exploratory?	

- [About H06. What learning preferences do people have?](H06-What-learning-preferences-do-those-people-have.md)
- Key points: We found that people's general work preferences and communication styles did not necessarily match their learning preferences. For example, someone who enjoyed pair working might prefer solo learning, and the other way around. A person wanting to master a tool may want different media to when they want to accomplis the next task in a different too. H04, H05 and H06 are linked, but not the same.
- Quality in Use Attributes: Effectiveness, Flexibility.
- Product Quality Attributes: Learnability, User error protection, Recognizability.


## H07: Where?

Location affects availability of the tool. Offices, at home, on customer site, countries / time zones, behind firewalls, indoors, outdoors, quiet or noisy environments.	

- [About H07. Where will the tool be used?](H07-Where-will-the-tool-be-used.md)
- Key points: Think about geography, technical environment and physical environment. Location may be of the tool, the person, or the their co-workers. We found that people were sometimes blocked from successful use of the tool by constraints in all three areas; for example tools behind role-based firewalls, but mandated for use by people in that role.
- Quality in Use Attributes: Context coverage.
- Product Quality Attributes: Operability.


## H08: Workflows?	

Workflows describe the steps people take to complete a series of tasks. Workflows include tasks supported by the tool, and also tasks upstream and downstream from the tool, and routes into and out of pipelines.	

- [About H08. What workflows will the tool be part of?](H08-What-workflows-will-the-tool-be-part-of.md)
- Key points: Workflows transcend tools and individuals, weaving across and between teams and organizations. Workflows include tasks that could be supported by a tool, and also tasks upstream and downstream from the tool. Workflows are described by experts in texts such as standards, syllabi, training courses, text books, blogs, etc. but those descriptions do not always reflect the reality of what people need to do.
- Quality in Use Attributes: Effectiveness, Context coverage.
- Product Quality Attributes: Operability, User goals, Appropriateness, Maintainability, Functionality, Security, Compatibility, Recognizability.

## H09 Risks?

The domain and technology, as well as the organizational culture will affect the level of risk that people face, affecting their approaches, and the support they need from tools. 	

- [About H09. What risks are associated with those workflows?](H09-What-risks-are-associated-with-those-workflows.md)
- Key points This is very context dependant; think about what risks will the tool help to mitigate, what risks it won't mitigate... whether there are risks increased by using the tool, and whether those change for other people. In particular evaluate which of the quality attributes are most important for the customers and users of the tool, and therefore there is risk if the attributes are not delivered.
- Quality in Use Attributes: Freedom from Risk, Context coverage.
- Product Quality Attributes: Operability, Appropriateness, Performance, Maintainability, Reliability, Scalability.


## H10 Autonomy?	

Organizational culture, autonomy and authority; supporting solo, pair /group work; team’s confidence in their process (maturity, assurance, experience level, skills).	

- [About H10. What autonomy of work styles is allowed in those workflows and teams?](H10-What-autonomy-of-work-styles.md)
- Key points: Should the tool suport different styles of working (solo, paired etc) and should the tool allow workflows to be tailored? We found the answers to these questions depended on the domain and level of risk in an organization, as well as perceptions of the experience and confidence of the teams doing the work, and rules around user management in the tool.
- Quality in Use Attributes: Context coverage, Flexibility, Satisfaction.
- Product Quality Attributes: Operability, Accessibility, Maintainability, Security.


## H11 When?

Level of urgency during the SDLC, speed a person can work with the tool (blockers, accessibility), staging of tasks in the workflow (learning and retaining knowledge). 	

- [About H11. When will the tool be used?](H11-When-will-the-tool-be-used.md)
- Key points: There may be a different urgency on workflows supported by the tool at different times. Risks may change, perceptions of quality may change. Some people may require longer than others to complete what looks like the same workflow task: they might be working at a greater level of detail, they might be learning/onboarding, they might be using assistive technology that changes the way they receive and impart information, they may be waiting on other activities. We found organizations had expectations of how long tasks should take, which tools did not always support. We found frustrations at the level of support/speed of response from tools owners to tools users.
- Quality in Use Attributes: Efficiency, Context coverage.
- Product Quality Attributes: Operability, Accessibility, Appropriateness, Performance, Maintainability, Compatibility, Reliability, Recognizability.


## H12 How long?

How long to get return on investment (ROI)? Maintainability and reliability over time. Decommissioning.	

- [About H12. How long will the tool be used?](H12-How-long-will-the-tool-be-used.md)
- Key points: What is the life span of the tool? Think about how long it will be used for, how long it will be maintained. Think about the impact if it becomes shelfware. Can we move easily from this tool to another and move our data? Can we move this tool to another environment? What happens when it is decommissioned - can we move our test scripts for example?
- Quality in Use Attribute: Context coverage, Freedom from Risk.
- Product Quality Attribute: Portability, Maintainability.

## Need more information?

[The heuristics repository READ ME includes links to "how to use" information, flowcharts, and examples of how people have used the heuristics](https://github.com/hci-lab-um/heuristics-for-test-tool-design/blob/main/README.md)

[The quality attributes page](Qualityattributesv2.md) provides explanations and evidence for each of the quality in use and product attributes identified in the research as important to testers for their tools **at the date of the research** and is linked to from each heuristic.
