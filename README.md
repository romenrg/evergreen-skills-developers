# Evergreen Skills for Software Developers
[![Codeship Status for romenrg/evergreen-skills-developers](https://app.codeship.com/projects/57d86950-fee3-0136-cc17-56b6e41314e7/status?branch=master)](https://app.codeship.com/projects/322711)

This repository includes a list of "evergreen skills" that should serve as a fair assessment of skilled software engineers / developers.

The purpose of this work is to serve as an alternative resource for conducting technical interviews of software developers / engineers, when hiring. This document focuses on software development best practices, cross-framework principles and other portable skills; as opposed to the detrimental fixation on language trends and framework-specific knowledge that we often see in the industry.

Programming languages evolve constantly, companies change their tech stacks, frameworks quickly become outdated, and syntax-related questions can easily be looked up by skilled engineers in search engines in minutes, whenever they need it. So, does it make sense to focus on those aspects when interviewing candidates?

On the other hand, there are software development best practices, cross-framework technical principles and critical non-technical skills that cannot be easily googled, take time to learn, are "evergreen" and have a huge impact on engineer's performance. These are significantly better at reflecting the real value a software developer / engineer brings to an organization or team.

This repository is a derivative work of the following article: "[What Makes a Great Software Engineer](https://www.romenrg.com/blog/2018/12/29/what-makes-a-great-software-engineer)".

_This is a work in progress. Important knowledge might be missing, existing bullets can probably be improved and better grouping strategies could be found. For those reasons, any contributions (i.e. PRs) are welcome._ Please feel free to propose changes following [the contributing guideline](CONTRIBUTING.md).

## Table of contents

- [Non-technical skills](#non-technical-skills)
  - [Core skills](#core-skills-aka-soft-skills)
    - [Communication](#communication)
    - [Teamwork](#teamwork)
  - [Innovation & (self-)management skills](#innovation--self-management-skills)
    - [Development process](#development-process)
    - [Problem solving skills](#problem-solving-skills)
    - [Mindset](#mindset)
- [Technical skills](#technical-skills)
  - [General technical knowledge](#general-technical-knowledge)
    - [Principles](#principles)
    - [Data Structures](#data-structures) 
    - [Clean Code](#clean-code)
    - [Source Code Management](#source-code-management)
    - [Technical collaboration](#technical-collaboration)
    - [DevOps practices](#devops-practices)
    - [Other general technical knowledge](#other-general-technical-knowledge)
  - [Field-specific technical knowledge](#field-specific-technical-knowledge)
    - [Front-end development](#front-end-development)
    - [Back-end development](#back-end-development)
    - [Architecture & infrastructure](#architecture--infrastructure)
    - [Security](#security)
    - [Scaling & optimization](#scaling--optimization)
    - [Concurrency](#concurrency)


## Non-technical skills

### Core Skills (aka "soft" skills)

#### Communication

* Follow e-mail best practices (e.g. [some e-mail etiquette rules](https://www.grammarly.com/blog/email-etiquette-rules-to-know/))
* Follow chat best practices (e.g. [use threads to organize discussions](https://slack.com/intl/en-es/help/articles/115000769927-Use-threads-to-organize-discussions-) and [other best-practices from Slack](https://blog.rescuetime.com/slack-focus-guide/))
* [Minimize interruptions](https://jaxenter.com/aaaand-gone-true-cost-interruptions-128741.html)
* Be polite

#### Teamwork

* [Practice empathy](https://simpleprogrammer.com/empathy-software-developers)
* Keep low egos
* Be an active listener
* Be a good mentor
* Share knowledge
* Engage in constructive decisions

### Innovation & (self-)management skills

#### Development process

* Know about [Agile Software Development principles](https://agilemanifesto.org/principles.html)
* Be comfortable with iterative and incremental development
* Have self-organizing capabilities
* Avoid creating false expectations (e.g. with [time estimates](https://www.romenrg.com/blog/2015/09/28/why-asking-developers-for-time-estimates-in-software-projects-is-a-terrible-idea-and-how-to-bypass-it-with-scrum/))
* Focus on priorities and business value

#### Problem solving skills

* Applying the [Scientific Method](https://en.wikipedia.org/wiki/Scientific_method)
* Researching skills
* [Lateral Thinking](https://www.edwddebono.com/lateral-thinking)
* Abstraction
* Creativity
* [5 Whys](http://en.wikipedia.org/wiki/5_Whys)
* Risk management

#### Mindset

* Don't fear change
* Dare to fail
* Be a life-long learner
* [Critical Thinking](https://en.wikipedia.org/wiki/Critical_thinking) (be rational, question decisions, "let the facts do the talking")

## Technical skills

### General technical knowledge

#### Principles

 * Basic control structures and boolean algebra
 * OOP (Object Oriented Programming)
 * [SOLID](https://en.wikipedia.org/wiki/SOLID), [GRASP](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
 * Functional programming (pure functions, recursion,...)
 * [Declarative vs Imperative programming](http://amzotti.github.io/programming%20paradigms/2015/02/13/what-is-the-difference-between-procedural-function-imperative-and-declarative-programming-paradigms/)

#### Data structures

 * Basic structures (basic types, array, matrix, object...)
 * Caching / memoization
 * Hash codes, tokens, encodings (e.g. Base64)
 * [Stack vs heap](https://stackoverflow.com/a/80113/1213497) memory

#### Clean code

 * Self-explanatory code
 * Use good naming (for files, variables, classes, functions...)
 * Avoid long functions and classes
 * Extract complex boolean conditions into functions
 * Use lightweight documentation instead of inline-comments
 * [Semantic versioning](https://semver.org/)

#### Source Code Management

 * CVS (Control Version Systems) / SCM (Source Code Management) basics: branches, tags, centralized vs de-centralized,...
 * SCM vs repository management / hosting (i. e. [difference between Git and GitHub](https://stackoverflow.com/a/13321586))
 * Understand why versioning is important
 * Commit best practices ([micro commits](https://lucasr.org/2011/01/29/micro-commits/) / atomic commits, good descriptions...)
 * Feature branches (short-lived)
 * Trunk-based development
 * Dependency management (the importance of package managers, the risks of [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell),...)

#### Technical collaboration

* [Pull Request best practices](https://blog.github.com/2015-01-21-how-to-write-the-perfect-pull-request/)
* Focus on the relevant pieces when performing code-reviews
* [Pair Programming best practices](https://martinfowler.com/articles/on-pair-programming.html)

#### DevOps practices

 * Build automation 
 * Write automated tests
 * Differences between unit, integration and system tests
 * Test pyramid
 * Continuous Integration
 * [Continuous Delivery vs Deployment](https://www.romenrg.com/blog/2017/12/31/continuous-integration-delivery-deployment/)
 * Feature Flags / Feature Toggles
 
#### Other general technical knowledge 

 * Regular expressions (regex)


### Field-specific technical knowledge

#### Front-end development

 * DOM (definition, understanding, virtual DOM...)
 * Responsive design (purpose, advantages, progressive enhancement...)
 * API standards: REST / SOAP
 * State management (associated problems, stateless approach...)
 * MVC and derivatives
 * WebSockets

#### Back-end development

 * Relational databases (how they work, basic concepts...)
 * Batch processes / Cron Jobs
 * Database design
 * ORM
 * Session handling
 * Error Handling, Auditing and Logging

#### Architecture & infrastructure

 * Externalized Configuration
 * [Everything as code (i.e. Configuration as code, Infrastructure as code, Docs as code,...)](https://www.romenrg.com/blog/2019/12/31/everything-as-code/)
 * Microservices
 * Virtual machines vs Containers
 * Processes vs threads
 * Controller-agent / Primary-replica pattern
 * Client-server pattern
 * IAAS, PAAS, SASS

#### Security

 * Public-key cryptosystems (e.g. RSA)
 * Principle of least privilege
 * DoS / DDoS
 * SQL injection
 * Man-in-the-middle attack
 * XSS and CSRF
 * Authentication (JWT, SSO)
 * Authorization (RBAC, ABAC)

#### Scaling & optimization

 * Load balancing
 * Redundancy
 * Latency
 * Lazy loading

#### Concurrency

 * Race condition
 * Deadlock
 * Mutual exclusion

---

_This work is released by [Romén Rodríguez-Gil](http://romenrg.com/) under the terms specified in [this license file](LICENSE), based on MIT License._
