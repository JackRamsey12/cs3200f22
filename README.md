Fall 2022 CS3200 Syllabus

# CS3200 Organization of Programming Languages

## Fall 2022

There are thousands of programming languages, from A#.NET to ZPL and everything in between. Do you need to know all of them to be a good programmer/engineer/computer scientist? 

The goal of this course is to convince you that the answer to this question is no. In fact, many programming languages — while superficially distinct at the level of syntax — are actually quite similar once you take a closer look. 

This semester, we'll explore by boiling a number of programming languages down to a small set of more fundamental language features, including structured data, control, mutable state, (higher-order) functions, types, polymorphism, and objects. Once you understand how these features work in isolation, you'll start seeing them (or not!) in all your favorite programming languages. This, in turn, will make it easy to pick up new languages with minimal fuss. 

To learn many of these features, you'll be implementing them yourselves within a series of increasingly complex interpreters for small programming languages. The meta-language for programming and discussion is OCaml. 

## Prerequisites
CS 2650 and 3000, but also: Some mathematical maturity (at the level of "I've seen and done a few proofs before") and (most importantly) a desire to learn!

|                       |         Details      |
|-----------------------|----------------------|
| **Lecture**           | MWF 3:05-4:00pm in Porter 100 |
| **Instructors**        | Chang Liu (liuc@ohio.edu) and Alexander Bagnall (ab667712@ohio.edu) |
| **Office Hours**      | Liu: WF 4-5pm (BR202); Bagnall: MWF 12-1pm (Teams) |

## Textbook

No required textbook. Readings listed below are used throughout the semester.

[Book: OCaml Programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook/cover.html) (from Cornell) ([PDF](https://cs3110.github.io/textbook/ocaml_programming.pdf))


## Course Structure

We'll meet MWF from 3:05-4pm. Attendance in class is required.
Homework consists of programming assignments and Blackboard quizzes. We'll have both a traditional in-class midterm and a final.

### Grade Breakdown

| Component               | Percentage |
|-------------------------|-----|
| Programming assignments | 40% |
| Attendance and Quizzes  | 10% |
| Midterm exam            | 20% |
| Final exam              | 30% |

Blackboard will be used to report grades and to post lecture notes and reading material. Up-to-date information on all other aspects of the course (assignment due dates, etc.) will be posted on this website.

## Schedule

The schedule is subject to revision.

| Week                        | Topic                                 | Reading                        | Assignment |
|-----------------------------|---------------------------------------|--------------------------------|------------|
| Week 1 (22 Aug) | [Intro](introduction.md), OCaml | [OCaml 1](https://cs3110.github.io/textbook/chapters/intro/intro.html) | Complete the ["HelloWorld" exercise](starting-ocaml.md) - no credit; nothing to turn in. Due before Week 2. |
| Week 2 (29 Aug) | Functional programming basics | [OCaml 2](https://cs3110.github.io/textbook/chapters/basics/intro.html), Supplementary: [Programming in Standard ML 2.1, 2.2](http://www.cs.cmu.edu/~rwh/isml/book.pdf#chapter.2) | [PA0: Intro. to OCaml](pa/0.md) (Due by the End of Week 2, Friday Sept 2.)  | 
| Week 3 (5 Sep - Labor Day) | Data and Types | [OCaml 3](https://cs3110.github.io/textbook/chapters/data/intro.html), Supplementary: [Types as Sets](https://guide.elm-lang.org/appendix/types_as_sets.html) | [PA1: Lists](./pa/1.md) (11 Sep) <br> Q0 (9 Sep) |
| Week 4 (12 Sep) | Natural numbers | [OCaml 3.12](https://cs3110.github.io/textbook/chapters/data/nats.html), Supplementary: Natural Numbers (on BB) | Q1 (17 Sep) |
| Week 5 (19 Sep) | Higher-order programming | [OCaml 4](https://cs3110.github.io/textbook/chapters/hop/intro.html), Supplementary: [A tutorial on the universality and expressiveness of fold](https://www.cs.nott.ac.uk/~pszgmh/fold.pdf) (sections 1-3.1) | [PA2: Binary trees](pa/2.md) (25 Sep) |
| Week 6 (26 Sep) | Modular programming | [OCaml 5](https://cs3110.github.io/textbook/chapters/modules/intro.html) | Q2 (29 Sep) |
| Week 7 (3 Oct) | Program correctness | [OCaml 6](https://cs3110.github.io/textbook/chapters/correctness/intro.html) | [PA3: BSTs](pa/3.md) (9 Oct) |
| Week 8 (10 Oct) | Mutability and state | [OCaml 7](https://cs3110.github.io/textbook/chapters/mut/intro.html) | Midterm Exam (14 Oct) |
| Week 9 (17 Oct) | Red-black trees | [OCaml 8.3](https://cs3110.github.io/textbook/chapters/ds/rb.html) | [PA4: Scheme0 Core](pa/4.md) (23 Oct) |
| Week 10 (24 Oct) | Abstract syntax and parsing | [OCaml 9 (up to 9.2)](https://cs3110.github.io/textbook/chapters/interp/intro.html)| Q3 (29 Oct) |
| Week 11 (31 Oct Halloween) | Interpreters | [OCaml 9.3, 9.4](https://cs3110.github.io/textbook/chapters/interp/substitution.html) | [PA5: Scheme1](pa/5.md) (6 Nov) |
| Week 12 (7 Nov) | Types and typechecking | [OCaml 9.5](https://cs3110.github.io/textbook/chapters/interp/typecheck.html) | Q4 (12 Nov) |
| Week 13 (14 Nov) | TBD | TBD | [PA6: Typed Scheme1](pa/6.md) (20 Nov) |
| Week 14 (21 Nov) | TBD / Thanksgiving | TBD | No quiz |
| Week 15 (28 Nov) | TBD / Final review | TBD | No quiz -- study for finals! |
| Exam week (5 Dec) | **[FINAL EXAM](https://www.ohio.edu/registrar/final-exam-schedule)**: Wednesday, December 7, at 12:20 p.m.| | [PA7 (optional): Scheme2](pa/7.md) (10 Dec) |

Assignments are due in Blackboard at 11:59pm unless otherwise specified. **Q0**, **Q1**, etc., denote quizzes in Blackboard, generally due on the Fridays of weeks with no due programming assignments (PAs).

## Homework and Collaboration Policies

### Acceptable Collaboration Matrix

|            | Instructor/TA	| Noninstructor (e.g., Another Student) | 
|------------|----------------|---------------------------------------|
| ***You***  | All collaboration allowed | High-level discussion (of the problems, not your code!) allowed but only after you've started the assignment; must be documented in README as described below |

Unless otherwise noted, homeworks are due Saturdays by 11:59 p.m. Late homework assignments will be penalized according to the following formula:

* Up to 24 hours late: no deduction, for a max 2 late homeworks per student across the entire semester
* Homeworks later than 24 hours, or from students who have already turned in 2 late homeworks, will receive 0 points.

You may discuss the homework with other students in the class, but only after you've attempted the problems on your own first. If you do discuss the homework problems with others, write the names of the students you spoke with, along with a brief summary of what you discussed, in a README comment at the top of each submission. Example:

```
(* README Alex Bagnall, Assn #1 
I worked with X and Y. We swapped tips regarding the use of pattern-matching in Rust. *)
```

However, **under no circumstances are you permitted to share or directly copy code or other written homework material**, except with course instructors. The code and proofs you turn in must be your own. Remember: homework is there to give **you** practice in the new ideas and techniques covered by the course; it does you no good if you don't engage!

That said, if we find that you have cheated on an assignment in this course, you will immediately:

* Be referred to the Office of Community Standards (which may take disciplinary action against you, possibly expulsion); and
* Flunk the course (receive a final grade of F).

Students in EECS courses such as this one must adhere to the Russ College of Engineering and Technology [Honor Code](https://www.ohio.edu/engineering/academics/academic-integrity.cfm##code), and to the OU [Student Code of Conduct](http://www.ohio.edu/communitystandards/academic/students.cfm). If you haven't read these policies, do so now.

## Student Outcomes vs. Course Learning Outcomes

1. An ability to analyze a complex computing problem and to apply principles of computing and other relevant disciplines to identify solutions. Students will be able to:
* Design and implement structured data types to solve computational problems
* Design and implement higher-order functions to solve computational problems
* Use pattern-matching to analyze and compute on structured data
* Use recursion to write functions that manipulate recursive collection types such as abstract syntax trees and lists
* Use polymorphism to implement a generic collection type such as a symbol table
* Analyze and reason equationally about a functional program in order to prove its correctness

6. An ability to apply computer science theory and software development fundamentals to produce computing-based solutions. Students will be able to:
* Apply understanding of grammars and syntax trees to implement a parser for an extended arithmetic expression language that conforms to a BNF specification
* Apply understanding of inductively defined data types, pattern-matching, recursion, and programming language semantics to implement an interpreter for an extended arithmetic expression language
* Apply understanding of type systems, type judgments, and inductively defined typing rules to implement a type checker for an extended arithmetic expression language
* Apply understanding of programming language design and implementation to extend an existing implementation of a language (parser, type checker, interpreter) to support new language features such as higher-order functions, mutable references, or closures

## COVID-19 Policies

If you test positive or need to isolate or quarantine this semester, after you have taken care of yourself and followed all the steps in the OHIO COVID-19 Protocol, please notify me so that we can develop a plan for you to receive the necessary course content. COVID-related illness, quarantine, isolation, and remain-in-room directives are legitimate university absences, and I will work with you to manage your academic requirements and connect you to resources. If you feel that your class performance is being impacted by COVID-19, please contact Public Health Operations by email (PHO@ohio.edu). The University has information about resources available to help with quarantine and isolation here (https://www.ohio.edu/coronavirus/protocol).

## Accommodation

Any student who feels they may need an accommodation based on the impact of a disability should contact me privately to discuss your specific needs and provide written documentation from Student Accessibility Services. If you are not yet registered as a student with a disability, please contact Student Accessibility Services at 740-593-2620 or visit the office in 348 Baker University Center.
