
# Heuristic H12 How Long?

[◄ Go back to README](../README.md)



## Navigation hint (where you are in idea-t)

Theme Context?  

Keyword How long?

Question: How long will the tool be used?


## In brief:

This is a different time related question to H11, `When?' and is about the test tool itself, rather than the product under test.


## Expanding this heuristic
<details close>
  <summary>Click for quick start summary
  </summary> 

Think about: 
- The lifespan of the tool. 
    - Will the tool be used enough to gain a return on investment (ROI) in implementing it?
    - If the tool becomes shelfware this is an economic risk to the organization (part of Freedom from risk is freedom from economic risk).
    - How long will the tool be maintained?
    - How many people will use the tool in that time?
    - What consideration of decommisioning the tool and migrating artefacts to a new tool?
    - Sustainability over the lifetime of the tool - what resources will be required?
- The length of time a tool will run continuously without restarting, and therefore the level of reliability required.
- Getting off the tool and porting data to another tool.
- Single use or limited use tools versus long term investments have different ROI implications.
- "how long" across time zones for remote distributed teams.

</details>

<details close>
  <summary>Click for explanation of the heuristic
  </summary> 

Use this heuristic to help question the return on investment (ROI) for the money, effort, and time to implement the tool.  Also consider maintainability and reliability of the tool and tests over time.  

At some point the tool will be decommissioned and replaced. When is that going to happen? 
At some point the infrastructure on which the tool runs will be decommissioned and replaced. Will the tool continued to be used? How will data be migrated when the tool and infrastructure are decommissioned?

</details>

<details close>
  
  <summary>Click for sub questions and alternative questions
  </summary> 

### Sub questions and alternative questions

- How long will we support this tool? What is its expected lifetime?
- How quickly will we get ROI? Is this a short or long term endeavor?
- Will the usage of the tool change over time?
- How long will the tool be maintained for and who will do that maintenance?
- Is this a free tool or a paid-for tool? What investment is required in time/effort to get it implemented and in use, on top of any financial cost: ROI can be about more than cash.
- What else is affected by the tool's planned life expectancy?
- how long will it be maintained?
- how will decommissioning and transfer of artefacts be done?
- What resources (renewable and non-renewable) will be required and waste generated to keep the tool running over its usage and decommisioning? Is it the "cheapest option" for sustainability?
- Is the tool scaleable over time? How much will its use build up and are there resources to sustain that growth?
- If the tool is being used across multiple time zones by distributed teams does "how long" include tiime zone adjustments?
- Will you need to revisit the heuristics in 3 months, six months, a year? For example if the context for tools is changing.


### Not? 
How long before the tool is not needed?
 



### Else?

What else would meet the same goals, with a better ROI?



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

 We found that:
- A tool with the original purpose of serving a single person or team sometimes starts to be used by other people/teams and requires maintenance long after the original designers/builders stop needing to use it.
- Tools are often acquired and not used (shelfware) – no ROI.
- Tools may need to run continuously for long time periods without restarting.
- Accepted tool sets change over time, therefore on acquiring a tool think about how you will decommission it and migrate artefacts to a new tool.
- Tool builders need to consider the ROI of designing and building a new tool and of making changes to an existing tool.

- <i>``Switching to new versions and dependency management takes up time that could be better spent on the actual software we develop.''</i>

- <i>``Return on investment - is the time and money I'm going to invest in automation a task worth it</i>

- <i>``I'm an "fresh in testing" xxx and really want to become more technical. I started with tool but 2 other girls said that programming is too difficult so I showed them the option to record the "checking" process, and it was easier, but the platform have so many changes so the maintenance is too much effort. Now we're waiting for ... new version hopefully things will change that rapidly because a lot of mess front-end have will be pushed to back end''</i>

- <i>``Last year, we had problems with every upgrade, e.g. changing the database from MySQL to PostgreSQL; or dropping the SSL which forced us to put a reverse proxy to stay "https". As you can see, BIG things to find out at the time of the upgrade session. But I love that they make regular releases with substantial content and that they are shaping the products of the suite based on customers' feedback. In 3 years, it has improved a lot in small increments that let us see how they react to the actual needs of a tester.''</i>

- <i>``Question: have you ever avoided using a tool? Answer: ``due to upgrade/support issues''</i>

</details>

## How to answer this heuristic

<details close>
  
  <summary>Click for activities and quality attributes that help answer this heuristic
  </summary> 
  
### Activities

To understand the ROI required from the tool you need to understand *how long* the tool will be used and supported, so you can design in appropriate levels of maintainability.
By understanding *how long* the tool needs to run, you will be able to design in appropriate levels of reliability.


Activities, with links to useful external information:
- Make a business case for the tool, including a ROI calculation, for one example see the Test Automation Patterns wiki on [Test Automation Business Case](https://testautomationpatterns.org/wiki/index.php/TEST_AUTOMATION_BUSINESS_CASE).
- Make a tool maintenance plan and build in maintainability.
- Assess the reliability required from the tool.

### Quality Attributes

- Quality in Use Attribute: Context coverage, Freedom from Risk
- Product Quality Attribute: Portability, Maintainability

We have tabulated the [Quality in Use and Product Quality Attributes](add link TBD) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help wth understanding maintainability in two way - the maintainability of the tool itself, how long it will be supported, and the maintainability of tests, and how fast they will be changing.**


</details>

## Navigation hint (where in idea-t to go next)

[◄ Back to README](../README.md)

[◄ To H01 Why?](../Heuristics/H01-Why.md)  if you have identified stakeholders who might have goals you have not yet considered. 

[◄ To H02 Who?](../Heuristics/H02-Who.md)  because in identifying contexts you might identify stakeholders you had not considered.

[◄ To H07 Where?](../Heuristics/H07-Where.md)  because you may now have identified other places the tool will be used.

