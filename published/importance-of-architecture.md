---
title: Avoid the urgency trap 
subtitle: Or: Why architecture matters in software projects
domain: software-engineering-corner.hashnode.dev
tags: architecture, software-architecture, design-and-architecture
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1665328931237/kXGgAFOdK.jpg?w=1600&h=840&fit=crop&crop=entropy&auto=compress,format&format=webp
publishAs: romanutti
hideFromHashnodeCommunity: false
---

A software project generally has different stakeholders.

One obvious stakeholder is the customer. They commission software developers to build software that meets certain requirements. The customer's focus often lies on the **behavior** of the software: It should behave in a way that makes or saves money for the customer. Many software engineers consider this their main task. They believe their job is to implement functionality to meet businesses' requirements.

However, this ignores that developers are their software's stakeholders too. Software contains the term *soft*. It is intended to be soft: Changing software and their behavior should be easy - otherwise, we would have called it *hard*ware. When the business changes a requirement or aims for a new feature, that change should be easily accomplishable. We use **architecture** to structure our applications to minimize the efforts required to build and maintain a system. Because architectural aspects often require a technical understanding of the system, it is the task of the developer (and architect) to ensure architecture in a software project.

Both, implementing the behavior of the software and enforcing its architectural aspects require resources. As time and money are limited in software projects (at least those of which I have been a part), we ask ourselves which one to prioritize.

## The Mere-Urgency Effect a.k.a. Why We're Bad at Prioritization

Already President Dwight D. Eisenhower recognized that we have difficulties answering that question. At the 1961 Century Association, he stated:

> Who can define for us with accuracy the difference between the long and short term! Especially whenever our affairs seem to be in crisis, we are almost compelled to give our first attention to the urgent present rather than to the important future.

This observation was recently confirmed by a [study](https://www.researchgate.net/publication/327103488%5FThe%5FMere%5FUrgency%5FEffect) in the Journal of Consumer Research. Researchers examined how people decide what to work on when faced with tasks of mixed urgency and importance. Across five experiments, they observed the following pattern:
We tend to favor time-sensitive tasks over tasks that are less urgent, regardless of their long-term payoffs. This psychological quirk is called the *Mere-Urgency Effect.*

## The Long-Term View

In software projects, the software's behavior is usually urgent: If you ask the business managers, they'll say it's essential for the software to work. But this view can be challenged by examining the extremes. Look at the following example:

*If you develop an application that works perfectly but is impossible to change, then it won't work when the requirements change. The application will become useless.*

*If you develop an application that does not work but is easy to change, then you can easily make the application work - and keep it working when the requirements change. The application will remain useful.*

It's a software developer's dilemma that the customer often can not evaluate the importance of architecture. As a software developer we are stakeholders as well. It's in our responsibility and also in our interest to ensure architecture in software projects. If we neglect architecture, our applications will become cumbersome, changes will become expensive and we might end up in a non-operatable state.
