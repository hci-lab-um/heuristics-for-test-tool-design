# Quality Attributes

## What are quality attributes?
Quality attributes are properties of a product which affect how well the product performs. Generally a software system but it could be some other product or service.  
Some of these are Quality in Use Attributes: they refer to attributes that are a measure of how good the experience is of using the product. They include the effectiveness with which someone can carry out their task, their safety, the flexibility with which they can work. 
Others are technical or product attributes which are built into the product and which the building blocks contributing to how the quality in use is achieved. They include functionality, usability, performance, security and many others.  

NB: even as I write this, new standards are being developed, published, and discussed meaning there are several ways of dividing up the quality in use and product quality attributes. 
On this page, I am going to provide a simplified summary of some of the main quality attributes, plus notes from the research data. 
You can of course go to buy the new standard, [ISO 25019](https://www.iso.org/standard/78177.html) which has different defintions.
Or use this summary from TMAP of the previous version ISO 25010 with their additional defintions have added for AI and sustainability [Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics). 

## Quality Attributes in the research data
What makes a tool successful is definitely not just its functionality and technical attributes. Here’s some data from the research, also summarised in Table 1:

- 98% of the participants mentioned usability of the tools as a concern, issue or necessity with 511 mentions in all the data.
- 90% of the participants mentioned management and organizational issues as a concern, issue, and support being necessary with 377 mentions in all the data.
- all of the technical attributes of tools added together came to 466 mentons, by 91% of the particpants. That includes functionality.

Table 1: Themes: Organisational, Technical, Usability
|Theme                        |	Participants   | Frequency |
|:----------------------------|:--------------:|:---------:|
| Organisational Management   |101 (90.9%)     |377 (27.8%)|
| Technical Attributes        |	102 (91.8%)    |466 (34.4%)|
| Quality in Use / Usability  |	109 (98.2%)    |511 (37.7%)|


## Usability, Quality in Use and the User Experience

Quality in Use and Usability had the most frequent mentions in our data. Understanding how the different attributes are building blocks to the overall user expereince (UX) helps us to design in a better UX. A good User Interface (UI) is supported by interaction design, and contirbutes to usability, which also includes designing for the users' efficiency, effectiveness, support to meet their goals in their context. Usability is one contributor to quality in use, wich also includes flexibility in use and freedom from risk. QUality in use is also suppported by all the technical attributes, such as maintainability, erformance, security. QUality in use conributes to UX, wher also design should address trust, credibility, flow through tasks and the usefuless of the prodcut. All of this, influenced by past experiences, mantal models and personal circumstances leads to the lived experience, and gives rise to emotions. 

![Flowchart showing the relationship between UI design, usability, quality in use, UX and the lived experience. ][researchflow](r-flow.jpg)

[researchflow]: r-flow.jpg

The definitions from the Standard ISO 25010 Quality in Use are a useful starting point. I have used that rather than the newer standard because - at time of writing - you'll find material online and freely available that comments on and helps with this standard, whereas ISO 25019 is so new that there is not the coverage of it. Also I am not sure I find some of the new defintions in there easy to apply. In a real project you will probably want to consider a subset of these. If you want the formal definitions, look in the standard or on the [TMAP website](https://www.tmap.net/wiki/quality-characteristics).

TBD: this table needs multiple lines for one topic but it looks like markdown won't allow that. COncerned that the table will not be easy to understand with a screen reader - check out accessibility and markdown tables. 
|Attribute         | Subattributes                    | Comment |
|:-----------------|:---------------------------------|:--------|
|Effectiveness     |none                              |When someone is carrying out a task, using the software, how well does the software support them to carry out the task confidently, knowing they have not made mistakes, knowing they are achieving what they want to achieve, accurately and completely?|
|Efficiency        |none                              |When someone is carrying out a task, using the software, how much effort doees it take to carry out the task, and how much resource does it take?                  |
|Satisfaction      |Usefulness                        |When the person is using the software, how satified are they that the software contributes usefully to the task?|
|                  |Trust                             |Do people trust the software to be producing accurate results?   |
|                  |Pleasure                          |Does using the software give the person any pleasure?   |
|                  |Comfort                           |Is the person comfortable using the software?    |
|Freedom from risk |Economic risk mitigation          | will any stakeholder be more protected or less protected from economic damage? |
|                  |Health and safety risk mitigation | will any stakeholder be more protected or less protected from damage to their health, safety, life? | 
|                  |Environmental risk mitigation     | will the environment (society, natural world, resource usage, sustainability be more protected or less protected?  |
|Context coverage  |Context completeness              | Given everything above, have we thought not just about specified contexts of use but also about contexts beyond those initially explicitly identified.|
|                  |Flexibility                       |  How much can someone adapt the software to be suitable for their own context and way of working? |




| Attribute       | Frequency   | Percentage of QiU/Usability comments   | Percentage of all comments   | Notes | Formal Definition from TMAP based on ISO 25010|
|:----------------|:-----------:|:--------------------------------------:|:----------------------------:|:------|-----------------------------------------------|
|  Usability      |   511       |                                        | 37.7%                        |       |Usability is the degree to which a product or system can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use.                    |
| Operability     | 250         | 44.4%                                  | 18.5%                         |
| Learnability    | 125         | 22.2%                                  | 9.2%                          |
| User goals      |  97         | 17.2%                                  | 7.2%                          |
| User interface aesthetics |33 | 5.9%                                   | 2.4%                          | 
| Context         | 34          | 6.0%                                   | 2.5%
| Satisfaction    | 24          | 4.3%                                   | 1.8% 
| Appropriateness ||||not mentioned||
| Recognizability||||not mentioned||
| User error protection||||not mentioned||
| Accessibility||||not mentioned by survey or workshop participants, strongly discussed by expert reviewer. Legal and moral implications||
  

 



##Technical Quality Attributes
The technical attributes were mentioned often in the context of a problem that adversely affecting the overall user experience. The breakdown of technical attribute mentions in the data is in table 2. You can see that the attributes are in order of frequency, and the percentage given of the total number of technical comments and the percentage of all comments. Notice how low in the list functionalty comes; people don't want more functionality, they want the overall experience to be better for the functionality supplied.

Table 2: Technical Attributes Mentioned
| Attribute       | Frequency   | Percentage of technical comments   | Percentage of all comments   | Notes | Formal Definition from TMAP based on ISO 25010|
|:----------------|:-----------:|:----------------------------------:|:----------------------------:|:------|-----------------------------------------------|
|portability      |	138         | 29.6%                              |10.2%                         | Portabiliity includes installability, adaptability and replaceability: installation and set up problems, and being able to change to a new tool - for example uninstalling without knock-on problems was mentioned by testers participating the surveys and workshops. | Portability – The degree of effectiveness and efficiency with which a system, product or component can be transferred from one hardware, software or other operational or usage environment to another. |
|performance      |	102         | 21.9%                              |7.5%                          | Performance includes time behaviour, resource utilization and capacity |Performance efficiency – The performance relative to the amount of resources used under stated condition.|
|maintainability  | 68          | 14.6%                              |5.0%                          |Maintainability includes modularity, reusability, analysability, modifiability.  |Maintainability – The degree of effectiveness and efficiency with which a product or system can be modified by the intended maintainers.|
|functionality    | 57          | 12.2%                              | 4.2%                         | Functional completeness, Functional correctness, Functional appropriateness| - Functional suitability – The degree to which a product or system provides functions that meet stated and implied needs when used under specified conditions.|
|security	      | 46          | 9.9%                               |3.4%                          | confidentiality, integrity, non-repudiation, accountability, authenticity|Security – The degree to which a product or system protects information and data so that persons or other products or systems have the degree of data access appropriate to their types and levels of authorization.|
|compatibility	  | 39          | 8.4%                               |2.9%                          |co-existence, interoperability |Compatibility – The degree to which a product, system or component can exchange information with other products, systems or components, and/or perform its required functions, while sharing the same hardware or software environment.|
|reliability	  | 16          | 3.4%                               |1.2%                          |maturity, availability, fault tolerance, recoverability|Reliability – The degree to which a system, product or component performs specified functions under specified conditions for a specified period of time.|
  

## Standards and Reference Texts

[Summary of ISO 20510 from TMAP with links to additional attributes](https://www.tmap.net/wiki/quality-characteristics)
[Summary of the ISO/IEC 25000 series of standards](https://iso25000.com/index.php/en/iso-25000-standards)
[ISO 25019 portal](https://www.iso.org/standard/78177.html)

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Stuck in limbo with magical solutions: The testers’ lived experiences of tools and automation." In Proceedings of the 15th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, vol. 2, pp. 195-202. SCITEPRESS-Science and Technology Publications, 2020.

Evans, Isabel, Chris Porter, and Mark Micallef. "Scared, frustrated and quietly proud: Testers’ lived experience of tools and automation." In Proceedings of the 32nd European Conference on Cognitive Ergonomics, pp. 1-7. 2021.

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Test Tools: an illusion of usability?." In 2020 IEEE International Conference on Software Testing, Verification and Validation Workshops (ICSTW), pp. 392-397. IEEE, 2020.



