<a name="TopofPage"></a>
# H9 What risks are associated with those workflows?
[◄ Go back](README.md)

Theme: CONTEXT?

## Quick Start

- Heuristic Question: What risks are associated with those workflows?
- The domain and technology, as well as the organizational culture will affect the level of risk that people face, affecting their approaches, and the support they need from tools. 	
- Quality in Use Attributes: Freedom from Risk, Context coverage
- Product Quality Attributes: Operability, Appropriateness, Performance, Maintainability, Reliability, Scalability
- [Mapping Heuristics to Quality Attributes](Qualityattributesv2.md)

## Explanation and sub-questions

<details close>
    <summary>Click for further explanation</summary> 
    
How you address this heuristic is very context dependent; you might *'know the sea you are swimiming in'* but still you need to consider what risks will the tool help to mitigate, what risks it won't mitigate... whether there are risks increased by using the tool, and whether those change for other people. In particular evaluate which of the quality attributes are most important for the customers and users of the tool, and therefore there is risk if the attributes are not delivered.

There are several types of risk to consider, and varying attitudes to risk. The domain and technology, as well as the organizational culture will affect the level of risk that people face, affecting both their approaches, and the support they need from tools. Some organizations and some stakeholders will be risk averse (for example in a safety critical domain) and other organizations and stakeholders will be risk takers (for example in an entrepreneurial situation where being first to market is key). 

Think about:
-	Risks inherent to the domain within which the tool is to be used – for example safety critical, regulatory which may dictate tool design and implementation choices;
-	Risks to be mitigated within the workflows and the tool;
-	Risks that stakeholders want to take, how to support best decision making to take opportunities safely;
-	Risks associated with business goals for example time to market, reputation;
-	Risks to the people whose work will be changed by the tool, including perceived or actual risk of redundancy, and opportunities for them;
-	Risks increased because of flaws in the tool itself;
-	Risks associated with different quality characteristics of the tool: security, performance, scalability;
-	Risks associated with the systems/products under test that the tool will be used with - does the tool itself need to meet requirements because of the domain it will be used in?
-	Risks to society, the environment.


Key questions to ask yourself:

- Have you considered how the tool mitigates or creates different types of risk:
    -	Project risks (threatening the result of the project),
    -	Product risks (threatening the quality of the product), and 
    -	Risks related to the tool and the use of the tool - risks that arise from the tool.
- Have you considered blockers in the workflows and how the tool will remove them?
- Have you considered how to prevent the tool adding blockers to the workflow?
- Have you considered risks associated with where in the technology stack the tool will be used, and risks associated with transferring information across the technology stack?
- Have you considered risks associated with robustness of workflows, approaches and methods supported by the tool (depending on context risks may arise from either underdone or overdone levels of control - different risks that need to be balanced)?
- If this tool design and build is a side project, think about risks associated with maintaining it over time as a side project.
- Who else and what else is affected risks arising from this tool or these workflows?
- Who else and what else is affected by risks mitigated by this tool or these workflows? 

</details>

<details close><summary>Research points and Quotes</summary>

- Security is risk both when under- and over-done. We found that the combination of strict rules for environments and for tool use carries the risk of people not being able to access the tool; they were *'stuck in limbo'* - security is not just about preventing access but also about allowing access. Are the policies around the tool going to support use of the tool?
- Tools will be used over time, while the organization, people, market and technology change. Scaleability, portability and maintainability were all important attributes that participants mentioned. *Inability to react to change over time* is a risk for the organization and the team which the tool can mitigate or make worse. 
- Time to market is a risk: *'supposing the tool holds up the release … but the tool also should mitigate against being late in the release [we need] faster testing'* and *'removal of human error through automation of repetitive testing'*
- We found that attitude to risk can be affected both by role and by communication styles. When we asked about activities, nearly 20% of participants were actively involved in risk management activities, and saw assessing and reporting on risk as part of their role. Better integration of risk management was a request:

*``should be extendable/better community support/risk reporting/should support and have BDD integration''*

*``Testing is very very different in different companies. One difference I see is where the bias lies in terms of risks.  You could ask does your testing have a bias - towards verification of known risks, towards discovery and experiments, a balance view.''*

</details>

<details><summary>mini usage case for risks 1 - risk discussion not needed just now...</summary>

The participants noted they did not find this a useful question for the current context (maintenance changes to tooling) but they could see this discussion being useful *'if implementing security-based features such as two factor authentication would need to look at the risk heuristic more closely, or if building from scratch'*

</details>

<details> <summary> mini usage case for risks 2  - we need a deep dive! </summary>

In this case the risk discussion needed to be much more specific - they said they would need to build a tailored and much more specific risk list within their context. Their action after the initial read of the heuristics is to have deep dive into a risk workshop; the ideas in the heuristics explanations don't cover all risks deeply.

</details>

<details><summary>mini usage case for risks 3 - communication is changing... </summary>

In one study, the participants discussed that they are working on integrating tooling with another organization, but part of the challenge is working with that larger organization. We discussed the risks arising from different tools integrating together, and also from different perceptions and communication styles across the collaborating organizations; two risk workshops are needed, one about the technical risks for the tooling, and one for discussion of the larger scale business risk.

</details>


## Activities, tools and techniques to help answer the questions

[Back to Top](#TopofPage)

<details close>
  <summary> Click for activities </summary>

To understand how to address risk appropriately in your design choices, you will need to understand the stakeholders’ attitudes to risks. Think about the stakeholders you identified in [H02](H02-Who-will-use-or-be-affected-by-this-tool.md) to consider audit, compliance, and marketing stakeholders having different viewpoints on risk, for example.

Hold a Risk Workshop to identify and assess the risks. For example, you could use [Risk Storming](https://riskstorming.com/) as a workshop, or use [risk storming cards](https://www.ministryoftesting.com/testsphere/riskstorming), or [Would Heu-Risk It?](https://pejgan.se/wouldheu-riskit.html) cards.

We have tabulated the [Quality in Use and Product Quality Attributes](Qualityattributesv2.md) in a priority order based on the input from industry practitioners during our research. Use that data to help you focus on the optimal product attributes to meet the QiU/UX goals for your tool. We've included quotes from practitioners that you can use to help you understand your own goals, stakeholders, and contexts, plus a cross reference between the heuristics and the quality attributes. **These may help with understanding risk - there are a set of quality in use attributes about Freedom from Risk.**

Related to risk is your stakeholders' attitude to adoption of technology. Are they early adopters who may be willing to put up with some rough edges in order to engage with new technology, or are they more mainstream and looking for a a safe, reliable option. 
This could be linked to organizational styles you'll look at in [H10](H10-What-autonomy-of-work-styles.md) and views on agility, maturity, and other process concepts.

When investigating choices for a new tool, Moore's innovation curve can be a useful comparator. 
<details close>
<summary>Mini usage case with Moore's Curve</summary>

In one small study we asked participants to rank how innovative versus how established and well known they wanted their new tool to be. We can draw their responses on a graph overlaid on Moore's Innovation curve and find that *for this group* they are slightly more towards the early adopter side of the graph. This will be different depending on the group of personas for your tool. You could add attitude to innovation to your personas, based around the Moore's curve.

![The graph shows that Moore's innovation curve moves from a small number of innovators, a larger number of early adopters, then the large mainstream group, and a small number of laggards. The bar chart overlaid on the Moore's Curve shows that for the specific group in a specific team, the curve is skewed more towards early adoption.](innovationcurve.jpg)

[innovationcurve]: innovationcurve.jpg

</details>

Activities and links to external articles that may be useful:
-	Risk identification and assessment with Stakeholders;
-	Domain identification - will the proposed tool be used in any regulated or safety critical domains, and are there requirements from those domain's standards?;
-	Use the innovation diffusion model to think about personas with different perceptions of the risk of change - this could be as simple as drawing Moore's curve and plotting your personas onto it;
-	Identify what testing of the test tool is appropriate;
-	Use [humanity-centered design processes](https://www.interaction-design.org/literature/topics/humanity-centered-design) which includes environmental risk mitigation and the health and safety mitigation.
-   See Innovation Diffusion, for example look at Moore's "Crossing the Chasm" to understand where your stakeholders sit in the technology adoption cycle (see [Crossing The Chasm](https://en.wikipedia.org/wiki/Crossing_the_Chasm)) 
-   Think about the language your personas use, with this [blogpost about two vocabularies for two audiences from Seth Godin](http://sethgodin.typepad.com/seths_blog/2017/02/the-two-vocabularies-because-there-are-two-audiences.html)

</details>

[Back to Top](#TopofPage)
