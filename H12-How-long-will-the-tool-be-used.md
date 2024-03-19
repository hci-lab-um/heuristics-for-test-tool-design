# H12 How long will the tool be used?
[◄ Go back](README.md)

Theme: CONTEXT?

Heuristic Question: How long will the tool be used?

## Explanation and subquestions
This is a different time related question and is about the test tool itself, rather than the product under test.

Think about: 
- The lifespan of the tool. 
    - Will the tool be used enough to gain a return on investment (ROI) in implementing it?  
    - How long will the tool be maintained?
    - How many people will use the tool in that time? 
- The length of time a tool will run continuously without restarting, and therefore the level of reliability required.


Research Point:  We found that:
- A tool with the original purpose of serving a single person or team sometimes starts to be used by other people/teams and requires maintenance long after the original designers/builders stop needing to use it.
- Tools are often acquired and not used (shelfware) – no ROI.
- Tools may need to run continuously for long time periods without restarting.

*``Switching to new versions and dependency management takes up time that could be better spent on the actual software we develop.''*

*``Return on investment - is the time and money I'm going to invest in automation a task worth it?''*

*``I'm an "fresh in testing" xxx and really want to become more technical. I started with [tool] but 2 other girls said that programming is too difficult so I showed them the option to record the "checking" process, and it was easier, but the platform have so many changes so the maintenance is too much effort. Now we're waiting for new [tool] version hopefully things will change that rapidly because a lot of mess front-end have will be pushed to back end''*

*``Last year, we had problems with every upgrade, e.g. changing the database from MySQL to PostgreSQL; or dropping the SSL which forced us to put a reverse proxy to stay "https". As you can see, BIG things to find out at the time of the upgrade session. But I love that they make regular releases with substantial content and that they are shaping the products of the suite based on customers' feedback. In 3 years, it has improved a lot in small increments that let us see how they react to the actual needs of a tester.''*

*``Question: have you ever avoided using a tool? Answer: [named tool] due to upgrade/support issues''*

Key questions to ask yourself:
- How long will we support this tool? What is its expected lifetime?
- How quickly will we get ROI? Is this a short or long term endeavor?
- Will the usage of the tool change over time?
- How long will the tool be maintained for and who will do that maintenance?
- Is this a free tool or a paid-for tool? What investment is required in time/effort to get it implemented and in use, on top of any financial cost: ROI can be about more than cash.

## Activities, tools and techniques to help answer the questions
To understand the ROI required from the tool you need to understand *how long* the tool will be used and supported, so you can design in appropropriate levels of maintainability.
By understanding *how long* the tool needs to run, you will be able to design in appropriate levels of reliability.

We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help wth understanding maintainability in two way - the maintainability of the tool itself, how long it will be supported, and the maintainability of tests, and how fast they will be changing.**

Activities, with links to useful external information:
- Make a business case for the tool, including a ROI calculation, for one example see the Test Automation Patterns wiki on [Test Automation Business Case](https://testautomationpatterns.org/wiki/index.php/TEST_AUTOMATION_BUSINESS_CASE).
- Make a tool maintenance plan and build in maintainability.
- Assess the reliability required from the tool.

