---
layout: essay
type: essay
title: "Smart Questions, Why So Important?"
# All dates must be YYYY-MM-DD format!
date: 2025-06-10
published: true
labels:
  - Questions
  - ICS 314
  - StackOverflow
---

<img src="../img/stackoverflow.jpeg">

## Introduction

Communication is one the most important software engineering skills to develop, and asking questions the "smart way" is one of the most important commmunication skill for a software engineer. 

## What Are Smart Questions?

According to Eric Raymond, there are some guidelines for effective interaction with the open source community. In this case, we will be diving into StackOverflow. 

These are some rules that he mentioned:

1. Do your homework: Before asking, do research by searching online to solve the problem.
2. Choose the Right Forum: Select the appropriate platform
3. Be Clear and Specific: Make precise and informative subject headers, etc.
4. Be Informative: Provide all necessary details about your issue.
5. Interpret Answers: Understand how you can recieve and apply the solutions.
6. Handle Rudeness: Learn how to filter out unhelpful responses.

Here is an Example of a Smart Question:

```
Q:
What is an explanation for the performance characteristics of CLWB when sharing data between cores (Tigerlake)?

Goal
I would like to transfer a 32KiB buffer between two cores (C1 and C2) as fast as possible,
performing loads and stores at both cores.

Observation
A simple benchmark is devised: one core performs loads and stores of the buffer sequentially*. Once it has finished, it records the time taken,
then sets a flag to indicate that the other core ought to take over. It busy waits for the flag to be reset, before repeating this process.
Thus, the two cores ping-pong this buffer between their local caches. The mean of the recorded times is found to be:

EXPERIMENT 1
C1 averaged 9615 cycles, 3.452µs
C2 averaged 9624 cycles, 3.455µs

...

Target Specifications
The target CPU is a TigerLake 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz. It uses the Intel Willow Cove core {optim of Sunny Cove}.
It has 48KiB L1d cache, 4 cores, each with 2 threads.

The target OS is Ubuntu 24.04.2 LTS.

Code
An reproducible full example (from clang 20.1.0, built with -O3) is here on godbolt

...

Q&A
Q: Did you try other prefetch distances?
A: Yes. All 'reasonable' prefetch distances result in the same performance, unreasonably short or long prefetch distances see worse performance.

```

Here is the link to [Smart Question](https://stackoverflow.com/questions/79646975/what-is-an-explanation-for-the-performance-characteristics-of-clwb-when-sharing).


## What Is Not A Smart Question?

```
Q:
What should be the next step

Hi guys I hope you doing well ..I am really felling disappointed I have taken pytorch,tensorflow.datasience ,As well as Ibm Ai certificate
.After almost year of working Now I don't Know what is the next step or course recommend me to take it I.hope to get intuition from any expert here my goal to be an Ai engineer
..thank you guys

.. .Hi guys I hope you doing well ..I am really felling disappointed I have taken pytorch,tensorflow.datasience ,As well as Ibm Ai certificate
.After almost year of working Now I don't Know what is the next step or course recommend me to take it I.hope to get intuition from any expert here
..thank you guys

```

Here is the link to [Not So Smart](https://stackoverflow.com/questions/79661426/what-should-be-the-next-step).
