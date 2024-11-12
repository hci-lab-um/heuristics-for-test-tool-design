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

### Tool vendor designing or building a test tool

<details close>
  <summary>Tool vendor designing tool</summary>
  
You are designing and building this tool for someone else to use. How well do you understand the people who will be affected?
We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*

You might find it useful to start with the *Who?* questions and once you have identified your people, then ask *Why?* for each group of people. You will want to focus the *``Why?''* heuristic H01 on the people who will use the tool, but you also need to think about the goals for your commercial stakeholders.

You need to think carefully about how long the tool will be maintained and supported, and the ROI on this process and for the tool.

Your order to answer the heuristic questions could be: H02, then H01, then H12, followed by H03 to H11.

</details>

[Back to Top](#TopofPage)

### Open source test tool design and build

<details close>
  <summary>Open Source designing tool</summary>
  
You are designing and building this tool for someone else to use. How well do you understand the people who will be affected?
We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*
In this case you may also have other people taking part in building and maintaining the tool - designing for maintainability will be important.

You might find it useful to start with the *who?* questions and once you have identified your people, then ask *Why?* for each group of people. You need to focus the *``Why?''* heuristic H01 on the people how will use the tool, which may be yourself, and people with other requirements and preferences.

You need to think carefully about how long the tool will be maintained and supported, and the ROI on this process and for the tool.

ROI may not be cash-related - think about how much time the community around the tool will want to spend working on it.

*''The 12 heuristics of tool development helped me in preparing the workshop for the [tool] by checking what I did and did not think about this tool when I came up with the idea. During the workshop the 12 heuristics were available to the attendees and they could use it as inspiration when brainstorming about problems we would have to tackle when developing the tool.''* 

</details>

[Back to Top](#TopofPage)

### In-house test tools

<details close>
  <summary>In-house tool designing</summary>
  
You probably know *why* you want to build this tool, possibly with yourself in mind as the primary person using the tool, but have you thought carefully about *who else* might want to use it and why they might want to use it? Those other people may have different answers to the *'Why?'* heuristic so think about it both as 'Why do we...?' and 'Why do they...?'

It could be *anyone in the organization* which might be too hard to think about, so instead we use personas or archetypes to help us think about groups of people, and the different contexts in which they will use the tool.

If you are building the tool just for yourself, read the 12 heuristic questions, think about "who else?" and then put the heuristics to one side. When you find other people are using the tool, and you are having to support them, then spend some time to address the heuristics. Do not lose the opportunity to build yourself a useful tool, but do be prepared to come back to this. Research showed us that the heuristic questions would have changed how people might build a tool for themselves, and also could look daunting; *'If I had read the heuristics before I started I would have done things differently ... but maybe I wouldn't have built the tool...'* Don't lose the chance to build yourself a `quick and dirty' tool that saves you time. But do come back to these heuristics when other people start adopting the tool and you have to adapt and support it.

If you are building a tool for your team to use, discuss the 12 heuristic questions together and use them to guide the design.  Suggest you set a time box for the discussion and from that decide on the ROI for this process - how much time do you need to spend on the tool design? Drop into the detailed explanations for each heuristic to pick up on activities that look particularly pertinent.

If you are building a tool for multiple teams, to use across the organization, then you need to spend time on the design, do some of the suggested activities to understand the personas in your organization, and their various contexts. Follow the generic order for the questions, including the loopbacks between questions that you will find in the detailed explanations.

</details>

[Back to Top](#TopofPage)

### Using the Heuristics to Support Changes and Maintenance Decisions

<details close> <summary>Changes and Maintenance</summary>
  
We found when evaluating the heuristics in the industry case studies that teams maintaining tools or mature automation suites found they already had discussed some of the heuristics topics. However, which ones they needed to disucss in detail was *very* context dependent even within one organization. It was useful for these groups to have an initial meeting where they discussed all the heuristics fairly quickly to select which ones to then discuss in detail. One case study participant noted that their team had been: *'working together for years'* so they had a through understanding of each other and of the people using the automation, including their communication and learning preferences; they noted *'if a new person joined, it would be different.'*

</details>

[Back to Top](#TopofPage)

### Evaluating or choosing a test tool

<details close> <summary>Evaluating or choosing a tool</summary>
  
You could be evaluating the tool for your own use, for your team, or for the whole organization

We found during the research that people *buying* tools often forget to ask *Why* they needed the tool, and people *building* tools often forgot to ask *Who for?*

Start with the *Why?* question H01.

If you are only evaluating the tool for yourself, use the questions to help you think about whether there are topics where you need to dig deeper. You may want the evaluation process to be quite quick - just good enough.

If you are evaluating for a team, take time to think about the *Who?* and *Context?* heuristic questions, and consider that they may have different answers to H01 *``Why?''*.

You will probably cover the questions in the generic order. You might not do the activities yourself, but you may want to find out if your tool supplier has those UX activities in place. 

When thinking about the goal for the tool, it is worth considering financial goals. In one case study during development of the heuristics, the participants discussed whether the licence costs for the tool were in conflict with their financial goal of cost saving. They ran an initial meeting for 30 minutes using the heuristics to consider ``shall we evaluate this tool at all?''  Heuristics H01 and H02 can be used in this way to arrive at a shortlist of tools. 

<details close>
<summary>Mini usage case</summary>

Here is an example of a small group of testers using the heuristics as a frame for choosing a new tool to use for organizing an event. 
There are three diagrams, produced during the study, showing the build-up of information from planning, through collecting data, to analysing that and deciding on important characteristics for the tool.
**Diagram 1** There were about 12 people in the group, and they work together occasionally to organize and run a meet up to discuss testing. 
First, we focused on planning: we wanted to understand learning and problem solving styles (H05, H06), attitudes to change (H09), and level of busy-ness (H04) to help us understand how new/untested and how easy to learn the tool needed to be.
Then we thought about our context: Our values and how we wanted to communicate, our context for our activities, our technology preferences, and our goals and activities (H07, H08, H10, H11 and H12). 
We decided on a mixture of individual questions with Lickert Scales, card sorts, and flip chart discussions to get the information on these topics.

![alt text in document body.][cs1-a](cs1-a.jpg)

[cs1-a]: cs1-a.jpg

**Diagram 2** Once we had collected data on the people, organization, goals and activities we could start linking those together. We realised we were a group of experienced leaders, who prefer working solo, were time poor, and had a broad technical and working context across the group. We linked those to our goals and activities. We realised during this that we needed to look at how we behaved (our organizational norms) not just get a new tool: the key was communication and just getting a new tool would not solve that by itself.

![alt text in document body.][cs1-b](cs1-b.jpg)

[cs1-b]: cs1-b.jpg

**Diagram 3** Having linked the data together, we then mapped the results on to quality attributes, realising we needed to favour a tool that supported quality in use attributes of high effectiveness, high efficiency, high flexibility, high learnability. Further it needed to be compatible with a wide range of devices, support asynchronous communication and be future proofed. This diagram shows the main quality attribute requirements for the tool.

![alt text in document body.][cs1-c](cs1-c.jpg)

[cs1-c]: cs1-c.jpg

In this small study, we used an early version of the heuristics, and they were refined as a result, so the mapping is indicative rather than exact. The whole process took about 4 hours over 2 days for the group to collect and discuss the data and another 4 hours afterwards for one person to make the analysis and come up with the diagrams and a list of requirements for the tool.


</details>

</details>

[Back to Top](#TopofPage)

### Setting a Tooling Strategy

<details close> <summary>Tooling Strategy</summary>
  
A tooling strategy may include tools and also automation, and may include in-house, open source and vendor tools.

During the Case Studies to evaluate the heuristics, we watched two different situations where they were used to help with the strategy for tooling and automation. The two case studies were:

- a consultant planning a tooling strategy for customers choosing tools to acquire - intending to look at vendor or open source;
- a consultant working with an in-house team to agree the tooling strategy for building tools and automation for an enterprise organization.

We noticed that the heuristic ordering may be quite radically different in these contexts; it could even be worth asking "H12 How long will the tool(s) be used?" before any other question in order to understand whether a long term strategy or short term tactics are required. How much effort is it worth putting into a tooling strategy partly depends on how future-facing it needs to be.

H01 Why? and H02 Who? will still be vital questions, and with H03-H06 enable the strategy to consider roles, team and individual growth, and communication. The context questions may be focused on one specific context - a particulat organization or enterprise - and within that context, questions H07 to H11 will be more or less applicable depending on the complexity of the context.

The order of the heuristics could be for example: 
- H12 -> H01 -> H02 -> H07
- then revisit H02 -> H03 -> H04 -> H06
- then revisit H01 -> H05
- then revisit H07 -> H08 -> H09 -> H10 -> H11 -> H12

</details>

[Back to Top](#TopofPage)

### UX Maturity and the Heuristics

<details close> <summary>Maturity</summary>
  
We found in the Case Studies that if an organization is mature in its appraoch to UX that some of the heuristics are embedded in how people think about the design of tools. In this case you might find it useful to concentrate on the ``else'' variants of the subquestions to challenge preconceptions: Why else? Who else? Where else? and so on. Additionally you will find you can quickly assess which of the heuristics will add most value to your discussion, and then deep dive into those. 

</details>

[Back to Top](#TopofPage)

### Organization Size, Team Location, and the Heuristics

<details close> <summary>Organization Size</summary>
We found in the Case Studies that if an organization is small and co-located so that person to person communication is easy that the heuristics can be used very informally, perhaps with a checklist on the wall.
In larger organizations, or where multiple organizations are involved, or with geographical separation of team members, communications may need to be controlled more formally. Using the heuristics as an agenda for a meeting may be a useful starting point.

</details>

[Back to Top](#TopofPage)

### Other uses for the heuristics

<details close>
<summary>Other uses</summary>

Some of our case study participants discussed using the heuristics to manage discussions about tools in use or changes to tools and automation suites. The examples include:

- using the heurisitics during on-boarding team members to help them understand design decisions made for automation suites and tools;
- using the heuristics during discussions with stakeholders such as customers to ensure that the requirements for the tool were clear both for the customers and for the end users of the tool;
- using the heuristics to plan a pre-sales meeting about tooling requirements.

  One participant said ``it is a way to guide the discussion and open up the discussion''

  </details>

[Back to Top](#TopofPage)
