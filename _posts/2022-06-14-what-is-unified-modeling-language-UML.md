---
title: What is Unified Modeling Language (UML)?
tags: [UML, Documentation]
style: fill
color: primary
description: Unified Modeling Language (UML) is a language used in software engineering during the analysis and design phase. This post explains what is and why should be used.
---

## What is Unified Modeling Language (UML)?

Unified Modeling Language (UML) is a language used in software engineering during the analysis and design phase, it is suppose to be used in the implementation phase as well, but in the practice many times this is used only at the beginning, and is left behind as the project goes on, but we will review why is that in a different moment, UML is used as well for modeling business processes.

In a UML model we can find "classifiers" which describes a set of objects, where the object is an individual with state and relationships to other objects; "events" that describes a set of possible occurrences; and "behaviors" that describes the possible executions or actions that generate and respond to the occurrences of events, including accessing and changing the state of objects.

Let's imagine a family: Dad, Mom, Daughter and Son are the "classifiers", family itself is a "classifier" as well; swimming, jogging, playing soccer, playing basketball, are "behaviors" that each "object" or family member executes respectively when (event) alarm rings at 5 am.

<div align="center">

![Family](https://unsplash.com/photos/BIk2ANMmNz4/download?ixid=MnwxMjA3fDB8MXxjb2xsZWN0aW9ufDJ8NDM2NTk3M3x8fHx8Mnx8MTY1NTMyMDM1Nw&force=true&w=480)

</div>

## Why use UML?

Mission critical and core business applications must be carefully designed, taking in consideration all the "ities" to define a well-designed architecture with [Quality Attributes](https://towardsdatascience.com/architecting-for-the-ilities-6fae9d00bf6b), in that sense, modelling the applications before coding can assure that business logic is complete and correct, and end user needs covered.

> "Essentially, all models are wrong, but some are useful." ― George E.P. Box

It is required to have a common language that everybody can understand to avoid subjective interpretations with clear definitions. Even when scope or activities are well defined in standup meetings (in agile, for example), interpretations can vary if there is no clear blueprint; UML provides a model to avoid this issue, a language that software engineers can understand.

Besides this "common language", Unified Modeling Language have following benefits:

* Enables code reuse improving productivity - designing some part of the application as a collection of self-contained modules.
* Product quality can be improved, because the team will have same vision.
* Practicality - it is important and valuable that if any developer is moved to a different project, a new collaborator can be easily onboard.

## References

* [UML](https://www.uml.org)
* [Object Management Group](https://www.omg.org/)
* [Architecting For The -ilities](https://towardsdatascience.com/architecting-for-the-ilities-6fae9d00bf6b)
