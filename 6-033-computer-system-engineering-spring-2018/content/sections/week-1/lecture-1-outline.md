---
course_id: 6-033-computer-system-engineering-spring-2018
layout: course_section
menu:
  leftnav:
    identifier: 6f82dc951f470c80136fe66e5ce7c473
    name: Lecture 1 Outline
    parent: 70f007d84ae8a0b0ea4f00fa8931c506
    weight: 50
parent_title: 'Week 1: Operating Systems Part I'
title: Lecture 1 Outline
type: course
uid: 6f82dc951f470c80136fe66e5ce7c473

---

1.  Introduction to Systems
    *   What is a system?
    *   Complexity makes building systems difficult.
2.  Why is Complexity Bad?
    *   Limits what we can build.
    *   Causes lots of other problems.
3.  Mitigating Complexity
    *   We mitigate complexity with modularity and abstraction.
        *   Modular systems are easier to reason about, manage, change, improve.
        *   Modularity reduces fate-sharing.
        *   Abstraction lets us specify interfaces without specifying implementation.
        *   Good abstraction decreases the number of connections between modules.
4.  Enforced Modularity
    *   Soft modularity isn't enough.
    *   One way to enforce is with a client/server model.
        *   Reduces fate-sharing.
        *   Important: remote procedure calls (RPCs) != procedure calls (PCs).
            1.  Have to deal with different types of failure (network, server,..).
                *   These failures are tricky, but starting with a modular design will let us reason about them and deal with them.
5.  Other Goals
    *   Beyond complexity, we might also want: scalability, fault-tolerance, security, performance, etc.
    *   Starting with a good, modular design helps achieve these properties.
    *   Difficult to get all at once; there are trade-offs.