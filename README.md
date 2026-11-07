# Local-Search-Engine
Build a local search engines, that can search through a set of documents provided by terms, efficiently and interactively. Your GUI app can never freeze!

# Design Doc
Design document is file you describe all the designs you have such as UML diagrams, your plans. how to distribute the work in the team.  should have the following sections:

- Goals and Non goals. this is the section all of the expected system behaviors shall be listed; the performance of the system shall be measure. For example how fast it can process the documents. Please be realistic about the performance of your app. Some reference point you can use is how fast a browser is loading a page, doing a search. Or how fast a common search engine website can do a similar search. There will be some portion of the marks deducted, if the performance of the app is far below common users expectations.
Design. This is the place you make your core design for each use cases. This is also the place a lot of disagreement from the team will happen. Make those promising solutions documented. Make the call in the design which one is the chosen solution, and which ones are considered as alternative solutions. There should be reason why the proposed solution is chosen, based on design principles, design patterns, and system performance requirements. There will be point deductions if there is not a single alternative solution mentioned in the who project. 
- All use cases shall be documented as UML sequence diagrams
- Class diagram (not state diagram) shall be created
Implementation. Major class skeletons to point out. Any piece introducing complex code coupling in your code. Please explain them in this section. No need to write every single line of code here. Again, use some common senses. Imagine you need to have another team in this class to understand your code. Please document those tricky pieces in your code. 
Timeline and Responsibility. How the work is / shall be distributed in the team. How each person play a role here, and what are the major milestones for your project.
Adjustment. Any adjustment, including the requirement changes surfaced on Nov 9 shall be documented.


# Implementations
Other than the design doc directory. There should be at least two other top level directory

- /main  where the source code lives

- /test where the test code lives, and the test data lives.

Since this is a sizable project, java packages shall be used. A short tutorial about packages can be found here https://www.w3schools.com/java/java_packages.aspLinks to an external site. Following the MVC design patterns, at least 3 packages shall be created under main.

- /models (the data model classes); /controllers (the controller classes describing the business logics); /views (UI related components, and listeners). You can go further from here, to see whether you like to use other design patterns helping the code structures. 
