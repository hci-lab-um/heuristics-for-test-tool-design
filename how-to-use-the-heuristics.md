# How to use the heuristics
[◄ Go back](README.md)

This section tells you about different ways to use the heuristics in different situations.

The [Generic Use](#Generic-use) section shows the flow between heuristics, and what you will find in each heuristic's description. Suggest you read that first.

This is followed by sections that suggest how to use the heuristics in several common situations - these will be added to after each case study during the evaluations of the heuristics:

- if you are a [tool vendor designing or building a test tool](#Tool-vendor-designing-or-building-a-test-tool);
- if you are designing or building an [open-source test tool](#Open-source-test-tool-design-and-build);
- if you are designing or building a test tool to be used by you or your team [in-house](#In-house-test-tools);
- if you are using the heuristics to help you [choose or evaluate a test tool](#Evaluating-or-choosing-a-test-tool)

## Generic use

### Flowchart through the Heuristics
The heuristics group into three themes: Why? Why? and Context?

NB: you might want to time box how long you spend on each theme, explore them, and then decide whether to allow more time to work more deeply on discovery activities. One person who used the heuristics as a simple list for input to a workshop said *"They just help you talk about things."* You can keep it as simple as that!

Generally, you would start with answering the question "Why do we need this tool?" then move on to consider the group of "Who?" questions, and finally look at the Context questions. However, information you find out from the "Who?" and "Context?" questions mean you may need to revisit "Why?", because different stakeholders you identify may have different goals in different contexts. You need to iterate between "Why?" and "Who?". The flowchart summarises this.
![Flowchart showing the "Why?" question is followed by the "Who?" questions and then the "Context?" questions, with loop-backs to the "Why?" question.][flow2](h-flow2.jpg)

[flow2]: h-flow2.jpg

### Flowchart focused on the "Who?" Heuristics
Heuristics H02 to H06 are people-focused questions we found were often not considered and which appeared from our research data to be important factors in understanding testers'characteristics. Add this information to the data you already have about people for whom you are designing the tool. The flowchart summarizes the generic order for addressing this group of heuristics and how they fit with the other heuristic themes with iteration between the themes.

![Flowchart showing that the "Who?" questions start with an overall question to identify the stakeholders, then four questions to help understand more about their characteristics: level of experiences, communication needs, learning perspectives, and learning preferences. There are iterative loops between the "Who?" and the "Why?" questions, and an onward path to the "Context?" questions.][flow3](h-flow3.jpg)

[flow3]: h-flow3.jpg

### Flowchart focused on the "Context?" Heuristics
Heuristics H07 to H12 cover questions about the contexts within which your stakeholders work. They are aspects to the context that we found affect how people are enabled or blocked in their engagement with and use of tools. Add this information to the data you already have about the contexts within which people work and consider how this affects your design of the tool. The flowchart summarizes the generic order for addressing this group of heuristics and how they fit with the other heuristic themes with iteration between the themes.

![Flowchart showing that the Context questions start with a general "Where?" question, followed by 5 questions to understand more about the context: the workflows, risks, work styles, when the tool will be used, and how long for.  There are iterative loops between the "Context?" questions and back to the "Why?" question.][flow4](h-flow4.jpg)

[flow4]: h-flow4.jpg


### Navigating the Heuristic Explanations
Each Heuristic has a page with an overview explanation of the heuristic, the research evidence, and activities. You will find on each heuristics page:

- **Theme:** the heuristics are divided into three themes: *Why* do we need the tool? *Who* will use it? and *Context* the tool will be used in? - 
- **Heuristic question:** just to remind you where you are.
- **Explanation and subquestions:** provides you with some points to think about, and key questions to ask yourself. Also in this section, a finding from our research that supports this heuristic and a link to some research quotes and characteristics that will help you ground your understanding and decisions.
- **Activities, tools and techniques to help answer the questions:** A menu of useful techniques, linked to further information either within this repository or on the internet. 

### You can tailor this to suit you
Don't be limited by the questions or the activities list - you won't have to do them all, and you may have preferred alternatives.

If you want to tailor the heuristics to suit your context, please do - see the [licence](LICENSE) to see how to do that and remember to reshare your versions and tailoring.

The sections below show some ways to use the heuristics: 
- if you are a [tool vendor designing or building a test tool](#Tool-vendor-designing-or-building-a-test-tool);
- if you are designing or building an [open-source test tool](#Open-source-test-tool-design-and-build);
- if you are designing or building a test tool to be used by you or your team [in-house](#In-house-test-tools);
- if you are using the heuristics to help you [choose or evaluate a test tool](#Evaluating-or-choosing-a-test-tool)



### Tool vendor designing or building a test tool

You are designing and building this tool for someone else to use. How well do you understand the people who will be affected?
We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*

You might find it useful to start with the *who?* questions and once you have identified your people, then ask *Why?* for each group of people.

You need to think carefully about how long the tool will be maintained and supported, and the ROI on this process and for the tool.

Your order to answer the heuristic questions could be: H02, then H01, then H12, followed by H03 to H11.

### Open source test tool design and build

You are designing and building this tool for someone else to use. How well do you understand the people who will be affected?
We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*
In this case you may also have other people taking part in building and maintaining the tool - designing for maintainability will be important.

You might find it useful to start with the *who?* questions and once you have identified your people, then ask *Why?* for each group of people.

You need to think carefully about how long the tool will be maintained and supported, and the ROI on this process and for the tool.

ROI may not be cash-related - think about how much time the community around the tool will want to spend working on it.

### In-house test tools

You probably know *why* you want to build this tool, possibly with yourself in mind as the primary person using the tool, but have you thought carefully about *who else* might want to use it and why they might want to use it?

It could be *anyone in the organization* which might be too hard to think about, so instead we use personas or archetypes to help us think about groups of people, and the different contexts in which they will use the tool.

If you are building the tool just for yourself, read the 12 heuristic questions, think about "who else?" and then put the heuristics to one side. When you find other people are using the tool, and you are having to support them, then spend some time to address the heuristics. Do not lose the opportunity to build yourself a useful tool, but do be prepared to come back to this. Research showed us that the heuristic questions would have changed how people might build a tool for themselves, and also could look daunting; don't lose the chance to build yourself a quick and dirty tool that saves you time. But do come back to these heuristics when other people start adopting the tool and you have to adapt and support it.

If you are building a tool for your team to use, discuss the 12 heuristic questions together and use them to guide the design.  Suggest you set a time box for the discussion and from that decide on the ROI for this process - how much time do you need to spend on the tool design? Drop into the detailed explanations for each heuristic to pick up on activities that look particularly pertinent.

If you are building a tool for multiple teams, to use across the organization, then you need to spend time on the design, do some of the suggested activities to understand the personas in your organization, and their various contexts. Follow the generic order for the questions, including the loopbacks between questions that you will find in the detailed explanations.


### Evaluating or choosing a test tool
You could be evaluating the tool for your own use, for your team, or for the whole organization

We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*

Start with the *Why?* question H01.

If you are only evaluating the tool for yourself, use the questions to help you think about whether there are topics where you need to dig deeper. You may want the evaluation process to be quite quick - just good enough.

If you are evaluating for a team, take time to think about the *Who?* and *Context?* heuristic questions.

You will probably cover the questions in the generic order. You might not do the activities yourself, but you may want to find out if your tool supplier has those UX activities in place. 
