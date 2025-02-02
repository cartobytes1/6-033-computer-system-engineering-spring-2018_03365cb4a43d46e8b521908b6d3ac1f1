---
course_id: 6-033-computer-system-engineering-spring-2018
layout: course_section
menu:
  leftnav:
    identifier: c09c7d62696b071fffb088433fa31b32
    name: RON Assignment
    parent: 75800336c3a2ebee84a18bb126a5a60b
    weight: 310
parent_title: 'Week 6: Networking Part II'
title: RON Assignment
type: course
uid: c09c7d62696b071fffb088433fa31b32

---

For this recitation, you'll be reading most of ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)"[Resilient Overlay Networks (PDF)](http://nms.lcs.mit.edu/papers/ron-sosp2001.pdf)" by David Anderson, Hari Balakishnan, Frans Kaashoek, and Robert Morris. This paper explains how to build an overlay network on top of the existing Internet that has better properties or other features. Many Internet applications, such as peer-to-peer applications are built as overlay networks.

To guide you as you read:

*   Read Section 1 closely. It introduces the main goals of RON and summarizes the main results.
*   Skim Section 2. It gives support for the context and motivation of RON.
*   Read Section 3 closely. Make sure you understand each of RON's design goals.
*   Read Section 4, but don't get too stuck on 4.2.2. It's important that you understand that RON uses measurement to evaluate and select paths, less important that you closely scrutinize its equations.
*   Skip Section 5.
*   Skim Section 6. The main results of the paper are summarized at the end of the intro. You should understand how the authors evaluated RON to determine those results.
*   Read Sections 7 and 8. Section 7, in particular, addresses some criticisms of RON.

As you read, think about:

*   Why is RON able to overcome failures that BGP can't?
*   Why does RON collect different application metrics?
*   How far does RON scale?
*   Routing is normally done at the network layer, but RON (and BGP) operate at the application layer. What are the benefits and drawbacks of this change?

Questions for Recitation
------------------------

**Before you come to this recitation**, write up (on paper) a _brief_ answer to the following (really—we don't need more than a couple sentences for each question).  

Your answers to these questions should be **in your own words**, not direct quotations from the paper.

*   What is the goal of RON?
*   How was it designed to meet this goal?
*   Why do we need RON? (Or why do the authors believe that we need RON?)

As always, there are multiple correct answers for each of these questions.