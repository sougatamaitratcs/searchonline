# searchonline
Search Online Assignment

Approach to given assigment .

Project Approach 

At the beginning, first we need to create a plan to crate to each requirements and provide a verification or done criteria for each requirement. Here, I follow agile principle to design and develop and test given assignment. As per agile process I first create the stories   and assign story points and dependency on each story.

Please see story-v1.doc file for detail stories .

Design and Development Approach 

Once stories are done , started identifying all cross cutting and NFR concerns including logging / transaction /performance / deployment  and developing componenets for them .Then started identifying packages and low level classes and its responsibilities.
Once packages and classes are designed then looking for interactions among each classes and designing inetrafces for inetractions . It includes public interfaces as well in class to class inetraction interfaces. Once interfaces or contracts are designed and developed then started building behaviour of each methods . Finally write unit test cases and mocked all external communications during building unit test cases.  Once unit testing is done then buiilding docker file and create docker images out of it. 
Once docker images are produced then run these images and perform functional testing. 




