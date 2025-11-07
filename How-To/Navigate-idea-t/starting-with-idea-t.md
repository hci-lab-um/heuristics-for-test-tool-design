<a name="TopofPage"></a>
# How to use the heuristics
[◄ Go back](README.md)

This section tells you about different ways to use the heuristics in different situations.

We recommend you re-use the heuristics at intervals, perhaps have a quick discussion at regular intervals to decide if you need a deep dive into any of them.  

<details close>
<summary>Quick start approaches</summary>

  You might want to time box how long you spend on each theme, explore them, and then decide whether to allow more time to work more deeply on discovery activities. One person who [used a cut-down version of the heuristics as a simple checklist for part of a workshop](https://huddle.eurostarsoftwaretesting.com/ladybug-open-source-project-kick-off/) said *"They just help you talk about things."* You can keep it as simple as that!

You might want to adopt them as an agenda for a planning meeting, or as a checklist to aid fast insights, to help you decide which heuristics you want to use for a deep dive. Timebox that activity. 

</details>

[Introducing the heuristics into an organisation](introducing-the-heuristics.md) may require a little planning; you need to build trust through experimenting with them.

<details close>
<summary>Tailoring hints </summary>

Don't be limited by the questions or the activities list - you won't have to do them all, and you may have preferred alternatives.
You can add to them, tailor them, combine them to suit your context. If your context changes, go back to the original 12 just to re-check your tailoring.

You can make your organization a tailored heuristics checklist based on these heuristics and the sub-questions under each heuristic - we've found that depending on context sometimes people have extra subquestions and want to split one main heuristics into two, or that they feel they have a good understanding in a particular area and want to combine heuristics. 

Check the research points and explanations first - for example one case study participant wanted to combine **H04 Communication** with **H06 Learning preferences** but the research data indicates that communication preferences changed when people were learning new things, for example from paired to solo or vice versa, and from exploratory to guided or vice versa, we recommend keeping them separate.
If you do tailor, we recommend you come back to the orginal list and review your choices periodically, to make sure you are still on track.

In another case study, the heuristics H07 and H11 were combined: in that specific context asking **H07 Where?** dictated which environment was to be used, and asking **H11 When?** implied which test stage, which linked to a specific environment. In other case studies, these two questions were clearly different and needed to be answered separately.

If you want to tailor the heuristics to suit your context, please do - see the [licence](LICENSE) to see how to do that and remember to reshare your versions and tailoring.

</details>

<details close>
<summary>Mini usage case</summary>
  
One organization in a case study used the heuristics in a 1 hour discussion of a mature automation suite to ask ``do we all still agree we are going in the right direction'' and confirmed this, while another automation suite in a similar meeting identified some key communication and process challenges that were blocking progress and required a deep dive discussion - this was rescheduled for another day.
</details>

<details close> <summary>Navigating this page</summary>
  
The [Generic Use](#Generic-use) section shows the flows between heuristics, and what you will find in each heuristic's description. Sections are:
- [Flowchart through the heuristics](#Flowchart-through-the-heuristics);
- [Flowchart focused on the "Who?" Heuristics](#Flowchart-focused-on-the-Who-Heuristics);
- [Flowchart focused on the "Context?" Heuristics](#Flowchart-focused-on-the-Context-Heuristics);
- [Navigating the Heuristic Explanations](#Navigating-the-Heuristic-Explanations).

This is followed by sections that suggest how to use the heuristics in several common situations - these will be added to after each case study during the evaluations of the heuristics:

- if you are a [tool vendor designing or building a test tool](#Tool-vendor-designing-or-building-a-test-tool);
- if you are designing or building an [open-source test tool](#Open-source-test-tool-design-and-build);
- if you are designing or building a test tool to be used by you or your team [in-house](#In-house-test-tools);
- if you are [maintaining or making changes to a tool](#Using-the-Heuristics-to-Support-Changes-and-Maintenance-Decisions) you may find you need a subset, but that is very context dependent;
- if you are using the heuristics to help you [choose or evaluate a test tool](#Evaluating-or-choosing-a-test-tool);
- to help you [set a strategy for tooling](#Setting-a-Tooling-Strategy) - including test automation and test tool implementation;
- if you are working in an organization that has [high level of understanding and maturity in its UX practices](#UX-Maturity-and-the-Heuristics);
- some differences in usage depending on [organization size and location of team members](#Organization-Size-Team-Location-and-the-Heuristics);
- some [unexpected uses for the heuristics](#Other-uses-for-the-heuristics) that our case study particpants mentioned!

</details>

[Back to Top](#TopofPage)

## Generic Use - Flowcharts through the Heuristics

The heuristics group into three themes: Why? Who? and Context?

### Flowchart focused on the "Why?" Heuristic

<details close>
<summary>Why? flowchart</summary>

Generally, you would start with answering the question "Why do we need this tool?" then move on to consider the group of "Who?" questions, and finally look at the Context questions. However, information you find out from the "Who?" and "Context?" questions mean you may need to revisit "Why?", because different stakeholders you identify may have different goals in different contexts. You need to iterate between "Why?" and "Who?". The flowchart summarises this.
![Flowchart showing the "Why?" question is followed by the "Who?" questions and then the "Context?" questions, with loopbacks to the "Why?" question.][flow2](h-flow2.jpg)

[flow2]: h-flow2.jpg

</details>

[Back to Top](#TopofPage)

### Flowchart focused on the "Who?" Heuristics

<details close>
<summary>Who? flowchart</summary>

Heuristics H02 to H06 are people-focused questions we found were often not considered and which appeared from our research data to be important factors in understanding testers' characteristics. Add this information to the data you already have about people for whom you are designing the tool. The flowchart summarizes the generic order for addressing this group of heuristics and how they fit with the other heuristic themes with iteration between the themes.

![Flowchart showing that the "Who?" questions start with an overall question to identify the stakeholders, then four questions to help understand more about their characteristics: level of experiences, communication needs, learning perspectives, and learning preferences. There are iterative loops between the "Who?" and the "Why?" questions, and an onward path to the "Context?" questions.][flow3](h-flow3.jpg)

[flow3]: h-flow3.jpg

</details>

[Back to Top](#TopofPage)

### Flowchart focused on the "Context?" Heuristics

<details close>
<summary>Context? flowchart</summary>

Heuristics H07 to H12 cover questions about the contexts within which your stakeholders work. They are aspects to the context that we found affect how people are enabled or blocked in their engagement with and use of tools. Add this information to the data you already have about the contexts within which people work and consider how this affects your design of the tool. The flowchart summarizes the generic order for addressing this group of heuristics and how they fit with the other heuristic themes with iteration between the themes.

![Flowchart showing that the Context questions start with a general "Where?" question, followed by 5 questions to understand more about the context: the workflows, risks, work styles, when the tool will be used, and how long for.  There are iterative loops between the "Context?" questions and back to the "Why?" question.][flow4](h-flow4.jpg)

[flow4]: h-flow4.jpg

</details>


[Back to Top](#TopofPage)

### Navigating the Heuristic Explanations

<details close>
  <summary> Navigating the Heuristic Explanations</summary>
  
Each Heuristic has a page with an overview explanation of the heuristic, the research evidence, and activities. You will find on each heuristics page:

- **Theme:** the heuristics are divided into three themes: *Why* do we need the tool? *Who* will use it? and *Context* the tool will be used in? - **Heuristic question:** just to remind you where you are.
- **Explanation and sub-questions:** provides you with some points to think about, and key questions to ask yourself. Also in this section, a finding from our research that supports this heuristic and a link to some research quotes and characteristics that will help you ground your understanding and decisions.
- **Activities, tools, and techniques to help answer the questions:** A menu of useful techniques, linked to further information either within this repository or on the internet. 

</details>

[Back to Top](#TopofPage)
