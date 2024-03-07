# Quality Attributes

## What are quality attributes?
Quality attributes are properties of a product (generally a software system but it could be some other product or service) which affect how well the product performs.  
Some of these are Quality in Use Attributes: they refer to attributes that are a measure of how good the experience is of using the product. They include the effectiveness with which someone can carry out their task, their safety, the flexibility with which they can work. 
Others are technical or product attributes which are built into the product and which the building blocks contributing to how the quality in use is achieved. They include functionality, usability, performance, security and many others.  

NB: even as I write this, new standards are being developed, published, and discussed so there are several ways of dividing up the quality in use and product quality attributes. On this page, I am going to provide a simplified summary of some of the main quality attributes. You can of course go to the standard, which, or use the additional defintions some authors have added, or use an list by someone who disagrees with the standard - which was ISO 25010, now replaced - and redefined - in ISO 25019. References and links are at the end of this page.

## Quality Attributes in the research data
What makes a tool successful is definitely not just its functionality and technical attributes. Here’s some data from the research, also summarised in Table 1:

- 98% of the participants mentioned usability of the tools as a concern, issue or necessity with 511 mentions in all the data.
- 90% of the participants mentioned management and organizational issues as a concern, issue, and support being necessary with 377 mentions in all the data.
- all of the technical attributes of tools added together came to 466 mentons, by 91% of the particpants. That includes functionality.

Table 1: Themes: Organisational, Technical, Usability
|Theme                        |	Participants   |	Frequency |
|:----------------------------|:--------------:|:---------:|
| Organisational Management   |101 (90.9%)     |377 (27.8%)|
| Technical Attributes        |	102 (91.8%)    |466 (34.4%)|
| Quality in Use / Usability  |	109 (98.2%)    |511 (37.7%)|


The technical attributes were mentioned often in the context of a problem that adversely affecting the overall user experience. The breakdown of technical attribute mentions in the data is in table 2. You can see that the attributes are in order of frequency, and the percentage given of the total number of technical comments and the percentage of all comments. Notice how low in the list functionalty comes; people don't want more functionality, they want the overall experience to be better for the functionality supplied.

Table 2: Technical Attributes Mentioned
| Attribute       | Frequency   | Percentage of technical comments   | Percentage of all comments   |
|:----------------|:-----------:|:----------------------------------:|:----------------------------:|
|portability      |	138         | 29.6%                              |10.2%                         |
|performance      |	102         | 21.9%                              |7.5%                          |   
|maintainability	 | 68          | 14.6%                              |5.0%                          |
|functionality	   | 57          | 12.2%                              |4.2%                          |
|security	        | 46          | 9.9%                               |3.4%                          |
|compatibility	   | 39          | 8.4%                               |2.9%                          |
|reliability	     | 16          | 3.4%                               |1.2%                          |


## Quality in Use and the User Experience

The definitions from the Standard ISO 25010 Quality in Use are a useful starting point. I have used that rather than the newer standard because - at time of writing - you'll find material online and freely available that comments on and helps with thsi standard, whereas ISO 25019 is so new that there is not the coverage of it. Also I am not sure I find some of the new defintions in there easy to apply. In a real preject you will probably want to consider a subset of these. If you want the formal definitions, look in the standard or on the [TMAP website](https://www.tmap.net/wiki/quality-characteristics).

TBD: this table needs mulitple lines for one topic but it looks like markdown won't allow that. COncerned that the table will not be easy to understand with a screen reader - check out accessibility and markdown tables. 
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


## Product or Internal Quality Attributes

TBD: for the moment just a list. next step is to edit this. Put in order from the research priority list above.

- Functional suitability – The degree to which a product or system provides functions that meet stated and implied needs when used under specified conditions.
    - Functional completeness
    - Functional correctness
    - Functional appropriateness
- Performance efficiency – The performance relative to the amount of resources used under stated condition.
    - Time behavior
    - Resource utilization
    - Capacity
- Compatibility – The degree to which a product, system or component can exchange information with other products, systems or components, and/or perform its required functions, while sharing the same hardware or software environment.
    - Co-existence
    - Interoperability
- Usability – The degree to which a product or system can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use.
    - Appropriateness
    - Recognizability
    - Learnability
    - Operability
    - User error protection
    - User interface aesthetics
    - Accessibility
- Reliability – The degree to which a system, product or component performs specified functions under specified conditions for a specified period of time.
    - Maturity
    - Availability
    - Fault tolerance
    - Recoverability
- Security – The degree to which a product or system protects information and data so that persons or other products or systems have the degree of data access appropriate to their types and levels of authorization.
    - Confidentiality
    - Integrity
    - Non-repudiation
    - Accountability
    - Authenticity
- Maintainability – The degree of effectiveness and efficiency with which a product or system can be modified by the intended maintainers.
    - Modularity
    - Reusability
    - Analysability
    - Modifiability
    - Testability
- Portability – The degree of effectiveness and efficiency with which a system, product or component can be transferred from one hardware, software or other operational or usage environment to another.
    - Adaptability
    - Installability
    - Replaceability
 
## Standards and Reference Texts

https://www.tmap.net/wiki/quality-characteristics
https://iso25000.com/index.php/en/iso-25000-standards/iso-


Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Stuck in limbo with magical solutions: The testers’ lived experiences of tools and automation." In Proceedings of the 15th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, vol. 2, pp. 195-202. SCITEPRESS-Science and Technology Publications, 2020.

Evans, Isabel, Chris Porter, and Mark Micallef. "Scared, frustrated and quietly proud: Testers’ lived experience of tools and automation." In Proceedings of the 32nd European Conference on Cognitive Ergonomics, pp. 1-7. 2021.

Evans, Isabel, Chris Porter, Mark Micallef, and Julian Harty. "Test Tools: an illusion of usability?." In 2020 IEEE International Conference on Software Testing, Verification and Validation Workshops (ICSTW), pp. 392-397. IEEE, 2020.



