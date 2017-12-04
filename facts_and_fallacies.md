/////////////////////////////////////////////
////////////    Review     //////////////////
/////////////////////////////////////////////

Title: Facts and Fallacies of Software Engineering
Author: Robert L. Glass
Rating: 4 / 5 stars
Amazon link: [inserth here]

Review
This book gets 4 stars for being pleasant to read, well-structured, and efficiently impactful. I would have liked to see more studies supporting the facts and fallacies. A more accurate title for this book might be "55 Opinions and Fallacies Which are Probably Mostly Supported by Evidence". Since Glass has a ton of industry experience, academic experience, and he's written 25+ books it's probably safe to accept his opinions for facts. He is very aware that some facts and
fallacies will be controversial and addresses those dissenting opionions. The book also feels a little naive at times as it seems to argue that a lot of problems in software engineering are the result of management just not understanding engineering. I agree management could benefit by being more understanding of engineers, but it goes both ways and I think engineers need to be much more understanding of the realities of running a business. The number one takeaway from this book is how
valuable it is to be able to bridge the gap between engineering and management. If you are able to do that, and do it well, you will be extremely impactful in an organization.

Pleasant to Read
Glass's personality comes through in his writing which makes the book feel less academic and more fun to read (he is known as the "premier cermudgion" of software practice). The writing is informal, but gets right to the point. Also, the book is succinct and moves along pretty quickly - each fact or fallacy only covers a couple of pages. 

Well-Structured
Think of this book more like a table of contents. Each fact or fallacy is quickly summarized with a discussion and controversy. Then Glass provides references and sources if you want to look further. A lot of the sources are his own books. A lot of the sources are well-regarded books like the Mythical Man Month, Peopleware, and Refactoring.

Efficiently Impactful
This book gets right to the point which means you can read it fast, and still get a lot out of it. I found myself agreeing with most of the facts and fallacies, disagreeing with a few, and being surprised by a few new ideas. I learned the most from the sections about estimation and maintenance. I also loved his opinion that we should teach new programmers to program by having them read programs (not write them).

More Opinion than Fact
A lot of the so-called "facts" feel more like opinions. But they are probably right, so it doesn't matter much. Regardless, it would be nice to see more studies backing up the facts. For example, the fact that "For every 25 percent increase in problem complexity, there is a 100 percent increase in solution complexity" is a pretty extraordinary claim. It seems like it's probably true-ish, but it seems to clean-cut to be true. How can this be true in every setting? Another one is "Enhancements represent roughly 60 percent of maintenance costs." Is this really true? And how many studies have replicated these results? You'd need to go and do the due dilligence to be sure.

Conclusion
Overall, I highly recommend this book for software engineers and managers of software engineers. It is a quick read and will have an immediate pay-off. If you learn one thing from this book it is the importance of being able to explain to management why things should be done a certain way. If you can explain the why and explain it well you will have happy managers and happy engineers.

/////////////////////////////////////////////
//////  Facts and Fallacies listed out //////
/////////////////////////////////////////////

Facts
Chapter 1 - About Management
People
1. The most important factor in software work is the quality of the programmers.
2. The best programmers are up to 28 times better than the worst programmers.
3. Adding people to a late project makes it later.
4. The working environment has a profound impact on productivity and quality.

Tools and Techniques
5. Hype (and tools and techniques) is the plague on the house of software.
6. New tools and techniques cause an initial loss of productivity / quality.
7. Software developers talk a lot about tools, but seldom use them.

Estimation
8. One of the two most common causes of runaway projects is poor estimation.
9. Software estimation usually occurs at the wrong time.
10. Software estimation is usually done by the wrong people.
11. Software estimates are rarely corrected as the project proceeds.
12. It is not surprising that software estimates are bad. But we live and die by them anyway!
13. There is a disconnect between software management and their programmers.
14. The answer to a feasibility study is almost always "yes".

Reuse 
15. Reuse-in-the-small is a well-solved problem.
16. Reuse-in-the-large remains a mostly unsolved problem.
17. Reuse-in-the-large works best in families of related systems.
18. Reusable components are three times as hard to build and should be tried out in three settings.
19. Modification of reused code is particularly error-prone.
20. Design pattern reuse is one solution to the problems of code reuse.

Complexity
21. For every 25 percent increase in problem complexity, there is a 100 percent increase in solution complexity.
22. Eighty percent of software work is intellectual. A fair amount of it is creative. Little of it is clerical.

Chapter 2 - About the Life Cycle
Requirements
23. One of the two most common causes of runaway projects is unstable requirements.
24. Requirements errors are the most expensive to fix during production.
25. Missing requirements are the hardest requirements errors to correct.

Design
26. Explicit requirements "explode" as implicit (design) requirements for a solution evolve.
27. There is seldom one best design solution to a software problem.
28. Design is a complex, iterative process. Initial design solutions are usually wrong and certainly not optimal.

Coding
29. Designer "primitives" (solutions programmers can readily code) rarely match programmer "primitives"
30. COBOL is a very bad language, but all the others (for business applications) are so much worse.

Error Removal
31. Error removal is the most time-consuming phase of the life cycle.

Testing
32. Software is usually tested at best at the 55 to 60 percent (branch) coverage level.
33. One hundred percent coverage is still far from enough.
34. Test tools are essential, but many are rarely used.
35. Test automation rarely is. Most testing activities cannot be automated.
36. Programmer-created, built-in debug code is an important supplement to testing tools.

Reviews and Inspections
37. Rigorous inspections can remove up to 90 percent of errors before the first test case is run.
38. Rigorous inspections should not replace testing.
39. Postdelivery reviews (some call them "retrospectives") are important and seldom performed.
40. Reviews are both technical and sociological, and both factors must be accommodated.

Maintenance
41. Maintenance typically consumes 40 to 80 percent of software costs. It is probably the most important life cycle phase of software.
42. Enhancements represent roughly 60 percent of maintenance costs.
43. Maintenance is a solution, not a problem.
44. Understanding the existing product is the most difficult task of maintenance.
45. Better methods lead to more maintenance, not less.

Chapter 3 - About Quality
Quality
46. Quality is a collection of attributes
47. Quality is not user satisfaction, meeting requirements, achieving cost and schedule, or reliability.

Reliability
48. There are errors that most programmers tend to make.
49. Errors tend to cluster.
50. There is no single best approach to software error removal.
51. Residual errors will always persist. The goal should be to minimize or eliminate severe errors.

Efficiency
52. Efficiency stems more from good design than good coding.
53. High-order language code can be about 90 percent as efficient as comparable assembler code.
54. There are tradeoffs between size and time optimization.

Chapter 4 - About Research
55. Many researchers advocate rather than investigate.

Fallacies
Chapter 5 - About Management
1. You can't manage what you can't measure.
2. You can manage quality into a software product.

People
3. Programming can and should be egoless

Tools and Techniques
4. Tools and techniques: one size fits all.
5. Software needs more methodologies.

Estimation
6. To estimate cost and schedule, first estimate lines of code.

Chapter 6 - About the Life Cycle
Testing
7. Random test input is a good way to optimize testing.

Reviews
8. "Given enough eyesballs, all bugs are shallow." 

Maintenance
9. The way to predict future maintenance costs and to make product replacement decisions is to look at past cost data.

Chapter 7 - About Education
10. You teach people how to program by showing them how to write programs.
