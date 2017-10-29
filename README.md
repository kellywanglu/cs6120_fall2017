# CS 6120/4120: Natural Language Processing

**Time and Location:** Mondays from 6:00 pm to 9:00 pm in Behrakis Health Sciences Cntr 315

**Instructor**: [Lu Wang](http://www.ccs.neu.edu/home/luwang/), Office 258 WVH

**Staff and Office Hours**: 

* Prof. Lu Wang, Mondays from 4:30pm to 5:30pm, or by appointment, 258 WVH
* Tirthraj Maheshkumar Parmar (email: parmar.t@husky.neu.edu), Tuesdays from 1pm to 2pm, 462 WVH
* Vishruth Krishna Prasad (email: krishnaprasad.v@husky.neu.edu), Wednesdays from 3pm to 4pm, 462 WVH

**Discussion Forum**: [Piazza](http://piazza.com/northeastern/fall2017/cs6120/home), sign up at [piazza.com/northeastern/fall2017/cs6120](http://piazza.com/northeastern/fall2017/cs6120)

_______
## Important Announcement
[9/1/2017] We will have a quiz with 24 **simple** questions, 20 of them as True or False questions (relevant to probability, statistics, and linear algebra) in the first class (9/11/2017). This quiz will be graded, but will not be counted in your final score if you're enrolled in CS6120/CS4120. The purpose of this quiz is to indicate the expected background of students. 80% of the questions should be easy to answer. If you find yourself struggling with this quiz, it's possible that you need to catch up on the background or it may be preferable to take one or two preliminary courses. For students previously do not take any algorithm course (CS 5800 or CS 7800, see Prerequisites), an 80% or above is required to enroll in this course.

_______
## Course Description
This course aims to introduce fundamental tasks in natural language processing, and its recent advances based on machine learning algorithms (e.g., neural networks) and applications for interdisciplinary subjects (e.g., computational social science). The course materials are mostly delivered as lectures, and accompanied with reading materials. The students will be evaluated based on assignments, a **research-driven** course project, and an open-book final exam.

#### Textbooks and Reference
* Main Textbook:
 * Dan Jurafsky and James H. Martin, "Speech and Language Processing, 2nd Edition", Prentice Hall, 2009.
 * Third edition draft is available at [web.stanford.edu/~jurafsky/slp3/](http://web.stanford.edu/~jurafsky/slp3/).
 
* Other Reference: 
 * Chris Manning and Hinrich Schutze, "Foundations of Statistical Natural Language Processing", MIT Press, 1999
 
* Since many natural language processing problems are driven by machine learning techniques nowadays, we also highly encourage you to read machine learning textbooks:
 * Christopher M. Bishop, "Pattern Recognition and Machine Learning", Springer, 2006.
 * Tom Mitchell, "Machine Learning", McGraw Hill, 1997.
 
#### Prerequisites
This course is designed for graduate students majoring in computer science, linguistics, and other related areas. Students who take this course are expected to be able to write code in some programming languages (e.g., Python, Java, or C/C++) proficiently, and finish courses in algorithms (CS 5800 or CS 7800), multivariable calculus, probability, and statistics. Linear algebra is optional, but highly recommended.

_______
## Grading
Each assignment or report, both electronic copy and hard copy, is due at the beginning of class on the corresponding due date. Blackboard is used for electronic submission. Hard copies are submitted in class. Assignment or report turned in late will be charged 20 points (out of 100 points) off for each late day (i.e. 24 hours). Each student has a budget of 5 days throughout the semester before a late penalty is applied. You may want to use it wisely, e.g. save for emergencies. Each 24 hours or part thereof that a submission is late uses up one full late day. Late days are not applicable to final presentation. Each group member is charged with the same number of late days, if any, for their submission.

Grades will be determined based on three assignments, ten in-class tests, one course project, one open-book exam, and participation:

* Assignments (30%): three assignments, each of 10%
* Quiz (9%): nine quick in-class tests (taken place at the beginning of each lecture), each of 1%
* Project (23%): team of 2 to 3 students, proposal (3%), reports (5%+10%), final presentation (5%, with 2% as bonus if selected as best project by peer students, and 1% as bonus for runner-up)
* Exam (35%): open-book
* Participation (3%): classes, Piazza
 
_______
## Schedule
#### Sep 11
* Topic: Introduction, Language Models
* Slides: [[intro]](slides_cs6120_fa17/introduction.pdf) [[6pp version]](slides_cs6120_fa17/introduction_6pp.pdf) [[Language Model]](slides_cs6120_fa17/lm.pdf) [[6pp version]](slides_cs6120_fa17/lm_6pp.pdf)
* Reading: Ch1, Ch4.1-4.9 
* TODO: start thinking about projects and looking for teammates

#### Sep 18
* Topic: Text Categorization, Naive Bayes, Part-of-Speech Tagging, Sequence Labeling, Hidden Markov Models
* Slides: [[NB]](slides_cs6120_fa17/nb.pdf) [[6pp version]](slides_cs6120_fa17/nb_6pp.pdf) [[POS]](slides_cs6120_fa17/postag.pdf) [[6pp version]](slides_cs6120_fa17/postag_6pp.pdf)
* Reading: Ch5, Ch6.1-6.5, and [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf) from 3rd edition
* TODO: Assignment 1 is released. [[A1]](material_cs6120_fa17/a1.pdf) [[A1 datasets]](material_cs6120_fa17/a1_datasets.zip)

#### Sep 25
* Topic: Word Sense Disambiguation
* Slides: [[WSD]](slides_cs6120_fa17/wsd.pdf) [[6pp version]](slides_cs6120_fa17/wsd_6pp.pdf)
* Reading: Ch19-20



#### Oct 2
* Topic: HMM cont'd, Machine Learning Basics (Maximum Entropy, Feedforward Neural Networks)
* Slides: [[MLBasics]](slides_cs6120_fa17/mlbasics.pdf) [[6pp version]](slides_cs6120_fa17/mlbasics_6pp.pdf) 
* Reading: Ch6.6, Ch12.1-12.5
* Course project proposal due



#### Oct 9 (NO CLASS: Columbus Day)
* TODO: Assignment 2 is released. [[A2]](material_cs6120_fa17/a2.pdf) [[A2 datasets]](material_cs6120_fa17/hw2-sa-ds.zip)
* Assignment 1 is due.


#### Oct 16
* Topic: Formal Grammars of English, Syntactic Parsing, Dependency Parsing
* Slides: [[Parsing Part1]](slides_cs6120_fa17/parsing_part1.pdf) [[6pp version]](slides_cs6120_fa17/parsing_part1_6pp.pdf) [[Parsing Part2]](slides_cs6120_fa17/parsing_part2.pdf) [[6pp version]](slides_cs6120_fa17/parsing_part2_6pp.pdf) 
* Reading: Ch12.1-12.5, Ch13.1-13.4.1


#### Oct 23
* Topic: Vector-Space Lexical Semantics, Semantic Parsing, Combining Logical and Distributional Semantics
* Slides: [[Semantics Part1]](slides_cs6120_fa17/semantics_part1.pdf) [[6pp version]](slides_cs6120_fa17/semantics_part1_6pp.pdf)
* Reading: Ch20.7, and [http://web.stanford.edu/~jurafsky/slp3/15.pdf](http://web.stanford.edu/~jurafsky/slp3/15.pdf), [http://web.stanford.edu/~jurafsky/slp3/16.pdf](http://web.stanford.edu/~jurafsky/slp3/16.pdf)
* Coure project progress report due on Oct 26

#### Oct 30
* Topic: Semantics cont'd, Information Extraction
* Slides: [[Semantics Part2]](slides_cs6120_fa17/semantics_part2.pdf) [[6pp version]](slides_cs6120_fa17/semantics_part2_6pp.pdf) [[Information Extraction]](slides_cs6120_fa17/ie.pdf) [[6pp version]](slides_cs6120_fa17/ie_6pp.pdf)
* Reading: Ch22.1-22.2
* TODO: Assignment 3 is released.
* Assignment 2 is due.

#### Nov 6
* Topic: Question Answering, Text Summarization, Sequence-to-sequence Model, Machine Translation


#### Nov 13
* Topic: Sentiment Analysis, Opinion Mining, NLP and Social Media


#### Nov 20
* Topic: Dialog Systems and Chatbots, Advanced Dialog Systems
* Assignment 3 is due.

#### Nov 27
* Topic: Course Project Presentation


#### Dec 4
* Topic: Exam
* Project final report due on Dec 11


_______
## Academic Integrity 
This course follows the [Northeastern University Academic Integrity Policy](http://www.northeastern.edu/osccr/academic-integrity-policy/). All students in this course are expected to abide by the Academic Integrity Policy. Any work submitted by a student in this course for academic credit should be the student's own work. Collaborations are allowed only if explicitly permitted. Violations of the rules (e.g. cheating, fabrication, plagiarism) will be reported.


