---
content_type: page
description: This section provides the lecture notes from the course, the schedule
  of lecture topics, and review handouts on state machine syntax and semantics, and
  graphical object model notation.
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Lecture Notes
uid: 3a88398d-2539-09b4-c278-7feefc951a95
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Review Handouts
---------------

State machine syntax and semantics ({{% resource_link b118e731-2b17-5d91-ac75-a7dbab8fbd91 "PDF" %}})

Graphical object model notation ({{% resource_link 9c7aef0d-0aa5-b4a0-9eaa-c647f52598a7 "PDF" %}})

Topics by Session
-----------------

Notes for lecture 21 are not available.

### Abbreviations

JSP = Jackson Structured Programming

DPLL = Davis-Putnam-Logemann-Loveland (algorithm)

SQL = Structured Query Language

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
LECTURE NOTES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}


### Introduction

Basic Java syntax and semantics; overview of objectives and structure of the course


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 1b28909b-65a8-5d8d-86c7-20488990ca02 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}


### Classes

More Java: exceptions, input/output, classes, access control, static


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link fd5cc0db-961c-e244-13c9-704851f7c522 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}


### Subclassing and interfaces

Subclassing, inheritance, overriding, interfaces, packages; distinction between declared type and actual type; downcasting; anonymous classes


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 91a561df-90c5-9357-7604-e7422dc01263 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}


### Designing state machines

State machine design; graphical and textual notation; state machine semantics; parallel combinations of machines


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 91fcd7e2-093b-0e1d-30ff-c0dfd035a2bb "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}


### Implementing state machines

State machine implementation patterns; concurrency and queues; modularity and interfaces


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link ed5ae6bd-8dbf-10aa-55e3-e4b9dbdc4943 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}


### State machine invariants

Safety and liveness properties; state properties and invariants; inductive reasoning; computing the product machine of a parallel combination; state explosion; fault tolerance; interlocks and the idea of a trusted base


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 487ddb78-1190-45e2-ad59-28c5ff8b4007 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}


### Designing stream processors

Stream processing programs; grammars vs. machines; JSP method of program derivation; regular grammars and expressions


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 85d67307-1386-f87f-9e4c-89b10f4e3fea "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}


### Decoupling and interfaces

Modularity, decoupling, information hiding; module dependence diagrams; using interfaces for decoupling


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 259aaebf-a525-dbb0-8784-64c24a9735f3 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}


### Testing and coverage

Why software testing is hard; input space partitioning, boundary testing, state machine coverage, code coverage; test-first development and regression testing


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link bb64ed26-d955-58c0-3ee1-fd8fe1ac8548 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 1

The SAT problem and SAT solvers; a new paradigm of functions over immutable types; use datatype productions to model structured values; patterns for implementing datatypes (Variant as Class, Interpreter)


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link e8eb24a2-a335-b182-c357-54e53d8b0b88 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 2

Review of basic datatype patterns; a naive solver with backtracking search; design improvements with Facade, Option types, and a 3-valued logic


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 87522087-2c3d-e43a-4b91-40cac99ed357 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}


### Debugging

Techniques for avoiding debugging: assertions, modular development with unit testing, code reviews; strategies for debugging: reducing test cases, hypothesis-driven debugging, binary search; Heisenbugs


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link bc46bea8-1173-69ed-efd4-94fcb834e3a3 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 3

Abstract data types; representation independence; characterizing types by operations; encapsulation; examples of types used by DPLL solver; Factory Method pattern


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 35abfb64-3da1-4426-5ccf-0bc3a96edbc1 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}


### Rep invariants, equality, visitors

Advice on implementing types; rep invariants and abstraction functions; equality for immutable types; Iterator and Visitor patterns


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link a0efc3cd-f5a9-2b70-0db7-3090bf2365d8 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}


### Little languages

Representing behavior using data structures; language datatypes, visitors, functional objects, higher-order functions; solving a problem by creating a domain-specific language


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link adf19ced-0f0c-1287-b28d-2bbcd7d48618 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}


### Basics of mutable types

Heap semantics (aliasing, assignment, field setting); reachability and conceptual storage leaks; the Object Contract and equality properties; hash maps and their representation invariant; problems caused by mutation of keys


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 5a6830a9-4eaa-166e-2db4-b5e820498609 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}


### Event-based programming

Fundamentals of programming graphical user interfaces; view hierarchy, Composite pattern, Publish-Subscribe pattern, Model-View-Controller (MVC); pitfalls of event-based programming


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link bafbe510-b913-13d9-cca4-fc590f3add45 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}


### Designing a photo organizer

The relational paradigm; conceptual modeling; object model syntax and semantics; Mitchell and Webb on "unity of purpose"


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link fc2df1f1-c337-37d7-12b2-0ce670d7144a "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}


### Implementing a photo organizer

Implementation as object model transformation; key issue of where state resides; standard patterns; navigation, immutability and encapsulation; MVC considerations


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 536852e9-3574-5fda-fa96-6f405cea7916 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}


### Concurrency

Shared-memory and message-passing paradigms; race conditions and deadlock; using threads and blocking queues in Java; concurrency issues in graphical user interfaces


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link af4002ad-0532-6362-dc37-88fce9a33e2d "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}


### Usability

User interface design principles: learnability, visibility, efficiency, errors, simplicity; iterative design; sketching and paper prototyping; user testing


{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}


### Relational databases

Using a database to represent an object model; relational algebra and SQL; transactions


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link b5444ace-eb6a-67f4-1401-b254cce7cd96 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}


### Conclusion

Final words; courses and internships that might follow 6.005; winners of Project 3 awards; 6.005 quiz game


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 1bb173ac-0fc9-8098-1d33-851b7de8af6b "PDF" %}})
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}