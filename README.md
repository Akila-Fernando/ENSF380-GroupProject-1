# ENSF380 Group Project 1 <br>
Akila Fernando <br>
Rinad Hamid <br>
Sean Pham<br>

## Instructions

ENSF 380 WS 2025 

Group Project Submission 1 (Week 4) 

Instructions 

Work with your assigned group project group. Each team should submit a two-page PDF file containing a UML class diagram (page 1) and a demonstration of how the sample data would be instantiated (page 2). The UML diagram should show class names, visibility, attributes, data types, and default values. Because we have not yet studied class relationships, you are not expected to depict relationships between classes. An example 

of how to demonstrate the sample data is given below.  

The file should be named <Group #>.pdf - for example, group 5 should submit a file 5.pdf. The UML diagram should be easy to read (with minimal overlapping of arrows) and be created using the software of your choice[^1] (not hand-drawn).  

Task 

You are tasked with creating a disaster relief system. Following natural disasters such as hurricanes or earthquakes, people may need to be housed in temporary shelters. To aid in family reunification, it is necessary to keep track of where individuals are housed, and their relationship to family members, especially in the case of minor children. Family members might be located in other facilities, unaffected by the disaster but seeking information, or 

not yet located. All contact with relief services is logged. In addition to housing, people 

may receive supplies and medical care. Currently, the information is entered in a single 

text document which is emailed between different centres. Below are some examples of entries: 

- TELUS Convention Centre - 136 8 Ave SE 
- 2025-01-18 
- A child five years of age named Teruya (surname unknown) was found with a broken arm and taken to the centre, where he was treated. Height: 43 inches. Weight: 38 pounds. Appearance: black hair, brown eyes. He is alert but quiet, and speaks French and Japanese. He has been assigned a social worker (#2891).
- University of Calgary - 2500 University Dr NW 
- 2025-01-18 
- Freda McDonald (female, b. 1986-06-03), suffering from a twisted ankle and light burns. She was not accompanied by her husband, Jo Bouillon, who is travelling and presumed safe. She is looking for her children, Teruya, Jari, and Luis Bouillon. She was issued a personal toiletries kit and two sets of clothes. 
- Cornelia ten Boom (1972-04-15), sister Elisabeth (1965-08-19) and father Casper (1939-05-18) arrived at Pantheon. Elisabeth suffers from pernicious anemia. Cornelia and Elisabeth asked for volunteer duties. They were each issued a personal toiletries kit and two sets of clothing apiece. 
- 2025-01-19 
- Hans Massaquoi (male, b. 2006-01-19) entered with his mother, Bertha Nikodijevic (female, b. 1983-05-10). Neither had injuries, and both were issued a personal toiletries kit. 
- Dispatch centre 
- 2025-01-19 
- Joseph Bouillon (b. 1988-05-03) phoned from Paris seeking information on his wife, Freda McDonald, and children Luis, Jari, and Teruya.  

Evaluation criteria 

Your submission will be assessed for the following:

- Are all important concepts represented in the diagram?
- Are all classes appropriately named?
- Are all critical requirements represented?
- Are object oriented design principles (which have been taught so far) followed?
- Are programming design principles followed? 
- Does the diagram align with the data and described requirements?
- Are UML standards (which have been taught so far) adhered to?
- Is the diagram legible? 

Example of representing sample data

This example uses a different scenario. Imagine that the task was described thusly:

Create a system to keep track of competition animals and their riders. Initially, the system will focus on horses (Equidae Chordata), but it may eventually be expanded to include other mounts. Each horse is associated with one rider, but a rider can ride multiple horses for different competitions, although a horse can also have multiple skills. *Taylor (age 25), competitor number 1234, is known to ride Thunder for racing and Blaze for jumping and dressage.* Gemariah (23), competitor number 567, rides Dawn for jumping. 

In response to this prompt, a programmer created a UML diagram (shown below). We could then provide a representation of how the data in the above task description would be instantiated according to the UML diagram (you can ignore the relationship between the classes), as shown below: 

**Animal (1)** animalSpecies: horse animalFamily: Equidae animalPhylum: Chordata animalName: Thunder animalRider: *Rider (1)* skills: racing 

**Animal (2)** animalSpecies: horse animalFamily: Equidae animalPhylum: Chordata animalName: Blaze animalRider: *Rider (1)* skills: jumping, dressage **Rider (1)** 

riderName: Taylor riderRegName: 1234 age: 25 

Note that the numbers are used to clarify a reference to another object. Only the part of the example task shown in italics is depicted. 

![](Aspose.Words.45a468c6-779f-4182-939c-c21fdaed6ac3.001.jpeg)

[^1]: https://draw.io was used to create most of the diagrams used in slides and examples.