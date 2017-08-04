# CSE 355 Final Study Guide
Materials and sources that might help with studying for the ASU CSE 355 Summer 2017 Final Exam. <b>This page will continually be updated with new content.</b>

## Contents
* [Introduction](#introduction)
* [Chapter 1: Regular Languages](#chapter-1-regular-languages)
* [Chapter 2: Context-Free Languages](#chapter-2-context-free-languages)
* [Chapter 3: The Church Turning Thesis](#chapter-3-the-church-turning-thesis)
* [Chapter 4: Decidability](#chapter-4-decidability)
* [Chapter 5: Undecidability/Reducibility](#chapter-5-undecidabilityreducibility)
* [Chapter 7: Time Complexity](#chapter-7-time-complexity)
* [Other Resources](#other-resources)
* [Recitations](#recitations)
* [Previous Final Exam Review Session](#previous-final-exam-review-session)
* [Contributing](#contributing)

## Introduction
Materials in this repo are included for the sole purpose to study with in preparation for the ASU CSE 355 Final Exam for the Summer 2017 semester. I have no idea if these will be useful or helpful. I just want to do good on the final, man. 

There are six chapters from the book Introduction to the Theory of Computation (3<sup>rd</sup> Edition) that were covered in lecture and will be covered in the final exam. In this repo, each chapter is broken down into four sections:

* <b>Lectures:</b> Lectures are PDFs of Ryan Dougherty's notes for the Summer 2017 CSE 355 course. These notes should be considered the ASU gold standard and are the most important resource on this page. Along with the PDFs are Ryan's YouTube videos for each set of notes, some sectioned off by breaks, which he has graciously provided us.
* <b>Resources:</b> Resources are external sites or documents that cover the same topics in class. These external resources may teach concepts in different ways that may help you understand the material better. However, as they are taught differently, these resources' content must be taken with a grain of salt and you must make sure to refer to Ryan's lecture notes to make sure you understand the content as taught in class. Since TutorialsPoint and GeeksforGeeks cover virtually every topic in Theory of Computation, only the sections are listed. If a section is linked, 📓 will be placed next to it.
* <b>Sample Problems:</b> Sample problems consist of problems that were found on external sites. All problem sets contain solutions along with the problems. However, even though these solutions may be mostly correct, their formatting or procedures may differ than what is actually expected on the exam.
* <b>Recap:</b> This section recaps concepts and topics you should be familiar with after reviewing each chapter. These concepts and topics many not all appear on the exam. Thanks to user Motunrayo on Piazza for the list of topics.

The problem sets and midterm solutions from the 355 class were purposely left out of this repository as their solutions will not be made public. However, it is recommended that you go back and check these documents out for yourselves and retry these problems yourselves for optimal studying.

If you wish to make a suggestion or contribute to the repository, please see [Contributing](#contributing).

## Chapter 1: Regular Languages
The first chapter covers regular languages including topics like DFAs, NFAs, Product & Powerset Construction, Regular Expressions, Pumping Lemma, and Regular Grammar.

### Lectures
* [Theory of Computing & DFAs](./chapter1/01%20Theory%20of%20Computing%20&%20DFAs.pdf) ([YouTube](https://www.youtube.com/watch?v=EhGZ-1uBcoQ))
* [Operations & Product Construction & NFAs](./chapter1/02%20Operations%20&%20Product%20Construction%20&%20NFAs.pdf) (YouTube [1](https://www.youtube.com/watch?v=YC3xPYIjxkI) [2](https://www.youtube.com/watch?v=MsiKpf-cE1Y) [3](https://www.youtube.com/watch?v=TAMf1JSaAp0))
* [Powerset Construction & Regular Expressions](./chapter1/03%20Powerset%20Construction%20&%20Regular%20Expressions.pdf) (YouTube [1](https://www.youtube.com/watch?v=Qo4uIrIpW1A) [2](https://www.youtube.com/watch?v=zc-Pt0OviC4) [3](https://www.youtube.com/watch?v=EXLN2JUwPDs))
* [GNFAs & Pumping Lemma](./chapter1/04%20GNFAs%20&%20Pumping%20Lemma.pdf) (YouTube [1](https://www.youtube.com/watch?v=Dz8VMHAGYLI) [2](https://www.youtube.com/watch?v=5PA8VBG2tbY))
* [Regular Grammars](./chapter1/05%20Regular%20Grammars.pdf) ([YouTube](https://www.youtube.com/watch?v=Y-XHPjKM9mE)) (First half of lecture notes)

### Resources
* 📓 [Introduction (GeeksforGeeks)](http://www.geeksforgeeks.org/toc-finite-automata-introduction/)
* 📓 [CFG and CFL (GeekforGeeks)](http://www.geeksforgeeks.org/toc-chomsky-hierarchy/)
* 📓 [Automata Theory Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/index.htm)
* 📓 [Classification of Grammars (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/introduction_to_grammars.htm)
* 📓 [Regular Grammar (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/introduction_to_grammars.htm)
* [From DFAs/NFAs to Regular Expressions](https://pdfs.semanticscholar.org/f297/8c9662fc3231de2b3e201491d88b91917aae.pdf)

<i>Note: TutorialsPoint refers to NFAs as NDFAs</i>

### Sample Problems
* [DFAs Problem Set](https://courses.engr.illinois.edu/cs373/fa2011/problem_sets/ps_1_sol.pdf)
* [DFA Construction Exercises (1<sup>st</sup> & 2<sup>nd</sup> page)](http://cs.nyu.edu/courses/spring14/CSCI-UA.0480-004/Lecture20.pdf)
* [Pumping Lemma Problems with Proofs](http://www.cse.unt.edu/~tarau/teaching/AUTO/auto_sols16/problemsession04.pdf)
* [Pumping Lemma Examples](http://compquiz.blogspot.com/2009/11/pumping-lemma-examples.html)
* [Mixed Problems](https://cseweb.ucsd.edu/classes/wi00/cse105/hw2sol.pdf) <b>(really useful!)</b>

### Recap
By the end of this section, you should know how to
- [ ]  construct a DFA for a given language.
- [ ]  perform a product construction (union and intersection).
- [ ]  construct a NFA for a given language.
- [ ]  understand union, concat, and star operations for NFA's.
- [ ]  convert a NFA to a DFA using powerset construction.
- [ ]  convert a regular expression to a NFA.
- [ ]  convert a NFA to a regex using GNFA's.
- [ ]  use the pumping lemma to prove a language is not regular.
- [ ]  give a regular grammar for a given language.
- [ ]  convert a DFA into a regular grammar.
- [ ]  convert a regular grammar into a NFA.


## Chapter 2: Context-Free Languages 
### Lectures
* [Context Free Grammar & Chomsky Normal Form](./chapter1/05%20Regular%20Grammars.pdf) ([YouTube](https://www.youtube.com/watch?v=eOLbypzKqVk)) (Second half of lecture notes)
* [CNF Continued](./chapter2/06%20CNF%20Continued.pdf) ([YouTube](https://www.youtube.com/watch?v=RrNhES0FU14))
* [CNF Continued & Pushdown Automata](./chapter2/07%20CNF%20Continued%20&%20Pushdown%20Automata.pdf) (YouTube [1](https://www.youtube.com/watch?v=mX4wSprR0jQ) [2](https://www.youtube.com/watch?v=mH0x0v5C1tE))
* [PDA Continued & Pumping Lemma for CFLs](./chapter2/08%20PDA%20Continued%20&%20Pumping%20Lemma%20for%20CFLs.pdf) (YouTube [1](https://www.youtube.com/watch?v=f2meWusR164) [2](https://www.youtube.com/watch?v=p93tsI_bHNA))
* [PL for CFLs Continued](./chapter3/09%20Turing%20Machines.pdf) ([YouTube](https://www.youtube.com/watch?v=3FxvADTwcMc)) (1<sup>st</sup> & 2<sup>nd</sup> pages of lecture notes)

### Resources
* 📓 [CFG and CFL (GeeksforGeeks)](http://www.geeksforgeeks.org/toc-chomsky-hierarchy/)
* [Pushdown Automata (GeeksforGeeks)](http://www.geeksforgeeks.org/theory-of-computation-pushdown-automata/)
* 📓 [Context-Free Grammars (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/context_free_grammar_introduction.htm)
* 📓 [Pushdown Automata (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/pushdown_automata_introduction.htm)

### Sample Problems
* [Example Conversion to Chomsky Normal Form (2<sup>nd</sup> page)](https://courses.cs.washington.edu/courses/cse322/08au/lec14.pdf)
* [CFG/PDA Exam Sample Solutions (includes DFA/NFA content as well)](http://www.cs.loyola.edu/~jglenn/478/S2011/Homework/x1_practice_solutions.html)


### Recap
By the end of this section, you should know how to
- [ ]  write a CFG in CNF.
- [ ]  convert a CFG to a PDA.
- [ ]  convert a PDA to a CFG.
- [ ]  apply the pumping lemma for CFLs.


## Chapter 3: The Church Turning Thesis
### Lectures
* [Turing Machines](./chapter3/09%20Turing%20Machines.pdf) (YouTube [1](https://www.youtube.com/watch?v=3FxvADTwcMc) [2](https://www.youtube.com/watch?v=jd1ue4WD9pk))
* [Nondeterministic Turing Machines](./chapter3/10%20Nondeterministic%20Turing%20Machines%20&%20Enumerable%20Languages%20&%20Encodings.pdf) ([YouTube](https://www.youtube.com/watch?v=a9_TPfe4ViQ)) (First half of lecture notes)

### Resources
* [Turing Machine (GeekforGeeks)](http://www.geeksforgeeks.org/turing-machine/)
* 📓 [Turing Machine (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/turing_machine_introduction.htm)

### Sample Problems
* [Turing Machine Exam Solutions (includes topics from Chapter 4)](http://www3.cs.stonybrook.edu/~ram/cse303/final_sample_sol.pdf)

### Recap
By the end of this section, you should know how to
- [ ]  construct a Turing Machine for a given language.
- [ ]  variants of Turning Machines.


## Chapter 4: Decidability
### Lectures
* [Enumerable Languages & Encodings](./chapter3/10%20Nondeterministic%20Turing%20Machines%20&%20Enumerable%20Languages%20&%20Encodings.pdf) ([YouTube](https://www.youtube.com/watch?v=shC9M2rWzp4))  (Second half of lecture notes)
* [Decidable Languages](./chapter4/11%20Decidable%20&%20Undecidable%20Languages.pdf) ([YouTube](https://www.youtube.com/watch?v=FhMipGzMJ48)) (First half of lecture notes)

### Resources
* [Recursive and Recursive Enumerable Languages (GeekforGeeks)](http://www.geeksforgeeks.org/recursive-and-recursive-enumerable-languages/)
* [Decidability (GeekforGeeks)](http://www.geeksforgeeks.org/theory-of-computation-decidability/)
* [Language Decidability (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/language_decidability.htm)


### Sample Problems
<i>No sample problems found for this chapter. Found some? [Consider contributing.](#contributing)</i>

### Recap
By the end of this section, you should know how to
- [ ]  determine the decidability of a language.


## Chapter 5: Undecidability/Reducibility
### Lectures
* [Undecidable Languages](./chapter4/11%20Decidable%20&%20Undecidable%20Languages.pdf) ([YouTube](https://www.youtube.com/watch?v=RH7Hr6Pb25g)) (Second half of lecture notes)
* [Undecidability & Rice's Theorem](./chapter5/12%20Undecidability%20&%20Rice%27s%20Theorm.pdf) ([YouTube](https://www.youtube.com/watch?v=SoenZVhDgB4))
* [Rice's Theorem Continued & Linear Bounded Automata](./chapter5/13%20Rice%27s%20Theorem%20Continued%20&%20Linear%20Bounded%20Automata%20&%20Intro%20to%20P%20NP.pdf) ([YouTube](https://www.youtube.com/watch?v=NgY4edrGjqA)) (First half of lecture notes)

### Resources
* [Undecidability and Reducibility](http://www.geeksforgeeks.org/undecidability-and-reducibility/)
* [Undecidable Languages (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/undecidable_languages.htm)
* [Rice's Theorem (TutorialsPoint)](https://www.tutorialspoint.com/automata_theory/rice_theorem.htm)

### Sample Problems
<i>No sample problems found for this chapter. Found some? [Consider contributing.](#contributing)</i>


### Recap
By the end of this section, you should know how to
- [ ]  determine the undecidability of a language.


## Chapter 6: Advanced Topics in Computability Theory
<i>Chapter 6 was not covered in class and, thus, will not be covered in the final exam.</i>

## Chapter 7: Time Complexity
Topics covered in Chapter 7 are extra credit topics. There may be an extra credit problem on the test asking about one of these topics.
### Lectures
* [Intro to P/NP](./chapter5/Rice%27s%20Theorem%20Continued%20&%20Linear%20Bounded%20Automata%20&%20Intro%20to%20P%20NP.pdf) ([YouTube](https://www.youtube.com/watch?v=3d5h6SQteHs)) (Second half of lecture notes)
* [P/NP & Cook-Levin Theorem & CLIQUE](./chapter7/14%20P%20NP%20&%20Cook-Levin%20Theorem%20&%20CLIQUE.pdf) (YouTube [1](https://www.youtube.com/watch?v=3d5h6SQteHs) [2](https://www.youtube.com/watch?v=5GAAOI9F6r0))

### Resources
* [P & NP Class (TutorialsPoint)](https://www.tutorialspoint.com/design_and_analysis_of_algorithms/design_and_analysis_of_algorithms_p_np_class.htm)
* [Cook's Theorem (TutorialsPoint)](https://www.tutorialspoint.com/design_and_analysis_of_algorithms/design_and_analysis_of_algorithms_cooks_theorem.htm)
* [NP Hard and NP-Complete Classes (TutorialsPoint)](https://www.tutorialspoint.com/design_and_analysis_of_algorithms/design_and_analysis_of_algorithms_np_hard_complete_classes.htm)

### Sample Problems
<i>No sample problems found for this chapter. Found some? [Consider contributing.](#contributing)</i>


### Recap
By the end of this section, you should know how to
- [ ]  understand concepts of N/P, N/P-Hard, and N/P-Complete.
- [ ]  understand SPACE.

***
## Other Resources
* [Introduction to the Theory of Computation Solutions](https://docs.google.com/file/d/0B1pmMQxkzlYfU0dzZ2trbWl4bmM/edit): <i>This is a PDF of the solutions to problems in the book. It's suggested that you go through the problem sets for each chapter in the book and attempt to work out solutions before looking at this PDF. This link may be broken in the future if the PDF is removed.</i>
* [Practice Problems for Final Exam](https://web.njit.edu/~marvin/cs341/oldexams/practice-final-soln.pdf): <i>These practice problems are <b>not</b> for the ASU CSE 355 courses. However, even though these are practice problems for a NJIT final exam, a review of these problems showed they are similar to ones we've seen in class and on previous exams. Friendly reminder to take their procedures and approaches to the problems with a grain of salt and always follow the procedures taught in class.</i>

## Recitations
There were four recitations over the course of the semester. You can find the PDFs of the worksheets to these recitations in the Recitations folder on the 355 page. These PDFs don't have the solutions to the problems and there's no known video source of the recitations.

However, Ryan Dougherty has a [YouTube playlist](https://www.youtube.com/playlist?list=PLhDf93xuCzIHRsAK-GpPt_dHJBNvFS7Bf) of all his recordings for his Spring 2017 CSE 355 recitations. Most videos will look identical to others since Ryan had multiple recitations every week.

## Previous Final Exam Review Session
For the Spring 2017 CSE 355 class, Ryan held a final exam review session during class. The video can be seen [here](https://youtu.be/B78ZPXRseIU). Do note that some of the content may have changed since.

## Contributing
If you wish to help mantain, update, or fix the information in this repository, great! Please feel free to suggest external resources and sample problems, suggest typo fixes, etc. There are two ways you can contribute.
#### Create a new issue
Create a new issue and assign the appropriate label to it. I will get around to looking at your suggestion/fix and implement any changes if needed.
#### Submit a pull request
If you want to dive into the repo itself, awesome! Clone this repository, make any edits, and submit a pull request. I'll review the request and merge if I approve.