# IS593: Language-based Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr)
- Time: Mon/Wed 09:00 - 10:30
- Office hour: Mon 10:30 - 11:30, N5 #2321
- Location: N1 #114

## Course Description
This course teaches a series of topics to build safe software systems based on programming language theories and techniques. The course covers formal semantics of programming languages and state-of-the-art techniques to formally estimate software behavior to prevent security vulnerabilities beforehand. In addition, the course introduces new waves in language-based security, thereby encouraging students to imagine and realize secure and reliable programming systems.

## Grading
- Homework: 30%
- Project: 30%
- Midterm: 30%
- Final: 10%

## Textbook
- Lecture slides will be provided
- Xavier Rival and Kwangkeun Yi, [Introduction to Static Analysis: an Abstract Interpretation Perspective](https://mitpress.mit.edu/books/introduction-static-analysis), MIT Press, 2020

## Homework
This course includes programming assignments through which students will learn how to design
and implement program analyzers.
We will use Github/Github Classroom to provide skeleton code and manage submissions.
Make sure you have a Github account and get familiar with `git`.
If you are new to `git`, see this [book](https://git-scm.com/book/en/v2).
Students will use the [OCaml](https://ocaml.org) programming language for the assignments.

All submissions will be managed using Github.
For each assignment, a unique invitation URL for Github Classroom will be posted at [KLMS](http://klms.kaist.ac.kr).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late


## Project
Students will propose their own project topics in the middle of the semester
and present their final results at the end. The detailed notice will be announced after the mid term exam.

## Schedule (tentative)
|#|Topics|Reading|
|------|------|------|
|1|Introduction|[Chap. 1]|
|2|Formal Semantics of Programming Languages (1): Operational Semantics||
|3|Formal Semantics of Programming Languages (2): Denotational Semantics||
|4|Concepts in Language-based Security|[Chap. 2]|
|5|Abstract Interpretation (1)|[Chap. 3]|
|6|Abstract Interpretation (2)|[Chap. 4]|
|7|Design and Implementation of Static Analysis||
|8|Midterm Exam||
|9|Static Analysis for Advanced Programming Features|[Chap. 8.1], [Chap. 8.2]|
|10|Advanced Static Analysis Techniques (1): Iteration Techniques|[Chap. 5.2]|
|11|Advanced Static Analysis Techniques (2): Sparse Analysis|[Chap. 5.3], [[PLDI12](https://dl.acm.org/doi/abs/10.1145/2254064.2254092)]|
|12|Advanced Static Analysis Techniques (3): Modular Analysis|[Chap. 5.4], [[InferBo](https://research.fb.com/blog/2017/02/inferbo-infer-based-buffer-overrun-analyzer/)]|
|13|New Wave in Language-based Security (1): Program Analysis with AI|[[PLDI18](https://dl.acm.org/doi/10.1145/3192366.3192417)], [[PLDI19](https://dl.acm.org/doi/10.1145/3314221.3314616)], [[ICSE19](https://dl.acm.org/doi/10.1109/ICSE.2019.00027)]|
|14|New Wave in Language-based Security (2): Program Debloating|[[CCS17](https://dl.acm.org/doi/10.1145/3243734.3243838)]|
|15|New Wave in Language-based Security (3): Program Synthesis|[[PLDI18](https://dl.acm.org/doi/10.1145/3296979.3192410)], [[IJCAI19](https://www.ijcai.org/Proceedings/2019/0847.pdf)]|
|16|Project Presentation||
|17|Final Exam||
