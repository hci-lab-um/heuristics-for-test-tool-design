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

Key questions to ask yourself:
- How long will we support this tool? What is its expected lifetime?
- How quickly will we get ROI? Is this a short or long term endeavor?
- Will the usage of the tool change over time?
- How long will the tool be maintained for and who will do that maintenance?
- Is this a free tool or a paid-for tool? What investment is required in time/effort to get it implemented and in use, on top of any financial cost: ROI can be about more than cash.

## Activities, tools and techniques to help answer the questions
To understand the ROI required from the tool you need to understand *how long* the tool will be used and supported, so you can design in appropropriate levels of maintainability.
By understanding *how long* the tool needs to run, you will be able to design in appropriate levels of reliability.

Activities:
- Make a business case for the tool, including a ROI calculation, for one example see the Test Automation Patterns wiki on [Test Automation Business Case](https://testautomationpatterns.org/wiki/index.php/TEST_AUTOMATION_BUSINESS_CASE).
- Make a tool maintenance plan and build in maintainability.
- Assess the reliability required from the tool.

Tip: Look at the Quality in Use attributes before you prioritize the product attributes, to make sure you focus designing for the optimal product attributes to meet the testers’ QiU/UX requirements within their context for the tool.
