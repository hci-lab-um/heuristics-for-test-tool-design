<a name="TopofPage"></a>
# Personas and Archetypes

[◄ Go back to H02](H02-Who-will-use-or-be-affected-by-this-tool.md)

[◄ Go back to README](README.md)

## Description

Personas and archetypes help you understand and model the characteristics of the groups of people who will use the proposed tool. 
With a small number of users you may be able to interview them all. 
With a large population you need to use a method that helps you understand groups that represent your users. 
Two techniques you could use are personas and archetypes. 

You can:
-	Map personas around roles;
-	Map personas around preferences and perspectives; 
-	Map personas around communication and work styles;
    -	NB: Perspectives, preferences and styles may cut across roles rather than align with them;
-	Use sampling, or statistical methods based on usage data if this is an existing tool with analytics collected.

Heuristics [H03 to H12](README.md) help you add details to the characteristics of the personas, and understand their contexts.
The [Quality Attributes](Qualityattributesv2.md) information will help you enrich the personas.

<details><summary>Worked example of thinking about learning and communication preferences towards a set of personas</summary>

Suppose we are building a tool for a large group of people to use, and we don't know them, and cannot interview them. Ideally we might run workshops with a group, but depending on how we select the participants, and who is willing to take part we might not get a representative sample. We can use the heuristic questions and a classification tree to start us thinking about who might use the tool and what their preferences might be.

## Step 1: Heuristic H04 Communication Preferences

Heuristic H04 is about communication preferences, and if we don't know that about the people who we want to use the tool, we could model it based on - for example - the DISC profile, giving us four potential communication styles - Blue/conscientious, Green/caring, Red/dominant and Yellow/social.  That communication preference affects how they want to receive and give information. Blue and Green tend to be more introvert, reserved. Red and yellow tend to be more extrovert, outgoing. Blue and Red tend to be focused on process and results. Green and yellow are more focused on people.  We might imagine their tool interface preferences: blue might want a detailed spreadsheet, Red might prefer bullet points on a powerpoint slide, Yellow might enjoy a chatting channel such a Slack. Green might want to work in a group at a whiteboard...  Is it worth thinking about how a tool might allow data to be shared between interfaces that allow both detail and overview, and allow both individual and group work?

We could therefore start our personas by imagining at least one persona for each DISC preference, and start a claasification tree. 

![start of a classification tree with 4 branches, D I S C][personasegmentH04](personasegmentH04.jpg)

[personasegmentH04]: personasegmentH04.jpg

## Step 2: Heuristic H05 Learning for Mastery or Learning for Task Completion

Heuristic H05 asks us to think about what type of learning people want to do when engaging with the tool. Are they wanting to master the tool and invest in the time to do that? Or, do they have limited time and simply want to carry out the next task. Both are reasonable approaches, and the same person may want to take different approaches at different times, or with different tools. They might have constraints because of budget pressures or management expectations. They may want to try out the tool quickly and then commit to mastering it.

Therefore we might need quick-start routes, wizards, short task-based videos, and also training/apprenticeship routes for mastery.

We can draw another mini-classification tree to show this split in approaches.

![classification tree segment showing mastery and task-based as two learning goals][personasegmentH05](personasegmentH05.jpg)

[personasegmentH05]: personasegmentH05.jpg

## Step 3: Heuristic H06 Learning preferences

Different people prefer to learn in different ways, and this may match to their communication preferences or be different. people may move from group to solo preferences and back again depending on context.
There are three areas we could start to consider: solo or group learning, theory or practical learning and the preferred media. Remember this also includes preferences, accessibility and also relates to H05 - for mastery we might want some theoretical basis, for task based we may prefer to be practical.

We can draw this in another classification tree segment,  breaking down as:

- Solo or group?
    - Solo
    - Group
        - pair learning
        - master - apprentice
        - teacher - group
        - ensemble     
- more theory or more practice?
    - more theoretical
    - more practical
- preferred media
    - video
    - audio
    - text
    - hands on 

This is shown in the figure below:

![classification tree segment matching list in text][personasegmentH06](personasegmentH06.jpg)

[personasegmentH06]: personasegmentH06.jpg

## Step 4: Putting H04, H05 and H06 together and selecting persona traits

Once we have those segments, we can assemble the whole classification tree, adn we find that we need 5 personas to cover all the options, because the learning preferences for solo and group break down into 5 branches.

The diagram shows we have named 5 persona groups with suggested preferences. This can make the basis of a fuller persona definition, tailored to our spefici context.

- Andy has Blue/C communication preferences, prefers solo learning, with theory in audio and text, to reach tool mastery
- Bill has Green/S communication preferences, preferes pair learning, practicall based, through video and hands-on, focused on completing the next task
- Carol has Red/D communication preferences, would like master/apprentice training that is practical, includes videos and hands-on learning, and is for tool mastery
- Dee has Blue/C communication preferences, would like a taught class, with some theory, through audio and text, for tool mastery
- Edi has yellow/I communication preferences, would like ensemble learning that is practical, hands-on, with supporting text and focused on the next task to be completed.

![][personasegmentcommsandlearning](personasegmentcommsandlearning.jpg)

[personasegmentcommsandlearning]: personasegmentcommsandlearning.jpg

</details> 

[Back to Top](#TopofPage)

## Rationale
### Research evidence
We found that people testing are a much wider and more heterogenous group than meets stereotypes for IT workers. We found that tools often were designed for a more narrow and stereotypical group.

To add to your personas, we have added quotes and other research points to each of the heuristics' explanations - Use these ideas as a "pick and mix" menu, for example:
- educational background: most of the people who took part had degree or postgraduate qualifications:
    - but 16% did not have a degree;
    - and although some of those with degrees had a software engineering qualification, many did not - degrees included arts, humanities, sciences, social sciences;
    - people's degrees didn't predict their role: 42% of Arts graduates in technical roles, 40% of Social Science graduates in technical roles, 44% of Science graduates in technical roles, 41% of IT graduates were NOT in technical roles; 
    - **Suggestion** include different educational backgrounds in your personas, and don't assume IT or software knowledge to help you think about learning support and communication preferences;
- work background: many of our participants had previously worked in non IT roles, sometimes in the domain for the software under test, sometimes not:
    - **Suggestion** include different work and background experiences in your personas to help you think about the language people use and their learning support requirements;
- learning preferences: different participants had different preferences for how to learn:
    - these did not necessarily match their usual communication preferences and styles;    
    - **Suggestion**  include solo versus group learning and problem solving preferences, include preferences for different media based on communication styles, use the examples in the heuristics to add to the personas.


### When to use this technique
Unless you have a small number of specific people using the tool, it will **always** be useful to make groupings by persona or archetype to help you identify the range of preferences, perspectives, styles and characteristics that people using the tool may have.

### Advantages
Gain a better understanding of people who will use the tool, while managing that in a small number of representative groups, rather than a myriad of individuals.

### Disadvantages
Takes time to do well.

[Back to Top](#TopofPage)

## Where do I find more information?

[Personas](https://www.interaction-design.org/literature/article/personas-why-and-how-you-should-use-them)

[Archetypes](https://radinadoneva.medium.com/behavioural-archetypes-instead-of-personas-c7ccc5b8b998) 

[NNGroup have a really useful summary with links to many ways of building personas](https://www.nngroup.com/articles/personas-study-guide/)

[Personas may be more or less broad in scope](https://www.nngroup.com/articles/persona-scope/)

Having got your personas or archetypes, you can build usage stories per persona, which can be [simple stories](https://www.interaction-design.org/literature/topics/user-stories) or [scenarios](https://www.interaction-design.org/literature/topics/user-scenarios) and you can build [empathy maps](https://xd.adobe.com/ideas/process/user-research/10-tips-develop-better-empathy-maps/).

[Back to Top](#TopofPage)
