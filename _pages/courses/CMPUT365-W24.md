---
layout: page
permalink: /courses/CMPUT365-W24/
title: CMPUT 365 Introduction to Reinforcement Learning (Winter 2024)
description: Introductory course to reinforcement learning at the University of Alberta 
nav: false
nav_order: 5
---

Class is held MWF 13:00-13:50 in CCIS 1-160.

<!-- [syllabus]({{ site.url }}/assets/courses/CMPUT365-W24/syllabus.pdf) -->

For this course we will be use Coursera as the main platform for the course. You will need to sign up for the course on Coursera and complete the assignments and quizzes there. The course will be split into three courera courses, each with its own modules, a set of assignments, and a set of quizzes. The assignments and quizzes will be completed on Coursera. 

You need to make sure you sign up for the private version of the course that corresponds to this session and not the public version of the course. Any work done on the public version of the course will not be transferred to the private version of the course. Please check with the instructor or TAs if you are unsure if you are on the correct version of the course.

<!-- Submit questions for in class answers [here](https://forms.gle/dN5omnbhDfDhXqXf6) -->

Coursera Courses:

1. [Funamentals of Reinforcement Learning](https://coursera.org/learn/fundamentals-of-reinforcement-learning)
2. [Sample-based Learning Methods](https://coursera.org/learn/sample-based-learning-methods)
3. [Prediction and Control with Function Approximation](https://coursera.org/learn/prediction-control-function-approximation)

Instruction Team:

- Scott Jordan (*Instructor*) <br>
  Email: sjordan <at> ualberta <dot> ca <br>
  Office hours: M 14:00-16:00 in ATH 3-21

- Shibhansh Dohare <br>
  Email: cmput365 <at> ualberta <dot> ca <br>
  Office hours: F 9:00-11:00 in CAB 313

- Esraa Elelimy <br>
  Email: cmput365 <at> ualberta <dot> ca <br>
  Office hours: Th 11:00-13:00 in CSC 3-26

- Gábor Mihucz <br>
  Email: cmput365 <at> ualberta <dot> ca <br>
  Office hours: W 9:00-11:00 in CAB 313

- Blanca Miller <br>
  Email: cmput365 <at> ualberta <dot> ca <br>
  Office hours: Tu 15:00-17:00 in CAB 313 

- David Szepesvari <br>
  Email: cmput365 <at> ualberta <dot> ca <br>
  Office hours: W 14:00-16:00 in CSC 3-50





<!-- Course Calendar (will be updated as the course progresses):


| Week | Date | Topic | Deadlines | Misc |  
| ---: |      | :---  | ---     | ---      | ---        |  --- |
| 1    | Mon, Jan 8  | Course Overview | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_1_overview.pdf)|
| 1    | Wed, Jan 10  | Background Review: Probability Statistics, Linear Algebra, and Calculus | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/lecture_2_review.pdf) |
| 1    | Fri, Jan 12  | Fundamentals of RL: An Introduction to Sequential Decision-making | Quiz: Sequential decision-making| [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_3_Bandits1.pdf) [Notebook]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture3_Bandits1.jl)|
| 2    | Mon, Jan 15  | Fundamentals of RL: An Introduction to Sequential Decision-making | | |
| 2    | Wed, Jan 17  | Fundamentals of RL: An Introduction to Sequential Decision-making | Program. Assignment (Bandits and Exploration / Exploitation)| [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_5_Bandits3.pdf) [Notebook]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture5_Bandits.jl) |
| 2    | Fri, Jan 19  | Fundamentals of RL: Markov Decision Processes (MDPs) | Quiz: MDPs| [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_6_MDP1.pdf)|
| 3    | Mon, Jan 22  | Fundamentals of RL: Markov Decision Processes (MDPs) | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_7_MDP2.pdf)|
| 3    | Wed, Jan 24  | Fundamentals of RL: Markov Decision Processes (MDPs) | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_8_MDP3.pdf)|
| 3    | Fri, Jan 26  | Fundamentals of RL: Value Functions and Bellman Equations | Quiz: Value Functions and Bellman Equations 1| [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_9_policy_value.pdf)|
| 4    | Mon, Jan 29  | Fundamentals of RL: Value Functions and Bellman Equations | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_10_BellmanEquations.pdf)|
| 4    | Wed, Jan 31  | Fundamentals of RL: Value Functions and Bellman Equations | Quiz: Value Functions and Bellman Equations 2 | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_11_Exercises.pdf) |
| 4    | Fri, Feb 2  | Fundamentals of RL: Dynamic Programming | Quiz: Dynamic Programming | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_12_DynamicProgramming1.pdf)|
| 5    | Mon, Feb 5  | Fundamentals of RL: Dynamic Programming | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_13_DynamicProgramming2.pdf)|
| 5    | Wed, Feb 7  | Fundamentals of RL: Dynamic Programming | Progamming Assignment: Optimal Policies with Dynamic Programming | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_14_DynamicProgramming3.pdf)|
| 5    | Fri, Feb 9  | Midterm Review | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_15_MidtermReview.pdf) |
| 6    | Mon, Feb 12  | Midterm | | |
| 6    | Wed, Feb 14  | Sample-Based Methods: Monte-Carlo Methods |  | |
| 6    | Fri, Feb 16  | Sample-Based Methods: Monte-Carlo Methods | Quiz: Off-Policy Monte-Carlo| [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_17_MonteCarloMethods1.pdf)|
| 7    | Mon, Feb 26  | Sample-Based Methods: Monte-Carlo Methods | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_18_MonteCarloOffPolicy.pdf)|
| 7    | Wed, Feb 28  | Sample-Based Methods: TD for Prediction | Quiz: Advantages of Temporal Difference Learning | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_19_TDprediction.pdf)|
| 7    | Fri, Mar 1  | Sample-Based Methods: TD for Prediction | |
| 8    | Mon, Mar 4  | Sample-Based Methods: Multi-step TD | | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_20_MultiStepTD.pdf)|
| 8    | Wed, Mar 6  | Sample-Based Methods: TD Lambda | Quiz: Advantages of Temporal Difference Learning | [Slides]({{ site.url }}/assets/courses/CMPUT365-W24/Lecture_19_TDprediction.pdf)|
| 8    | Fri, Mar 8  | Sample-Based Methods: TD for Prediction | | -->


