# Evergreen Skills for Software Developers
[![Codeship Status for romenrg/evergreen-skills-developers](https://app.codeship.com/projects/57d86950-fee3-0136-cc17-56b6e41314e7/status?branch=master)](https://app.codeship.com/projects/322711)

This repository includes a list of "evergreen skills" that should serve as a fair assessment of skilled software engineers / developers.

The purpose of this work is to serve as an alternative resource for conducting technical interviews of software developers / engineers, when hiring. This document focuses on software development best practices, cross-framework principles and other portable skills; as opposed to the detrimental fixation on language trends and framework-specific knowledge that we often see in the industry.

Programming languages evolve constantly, companies change their tech stacks, frameworks quickly become outdated, and syntax-related questions can easily be looked up by skilled engineers in search engines in minutes, whenever they need it. So, does it make sense to focus on those aspects when interviewing candidates?

On the other hand, there are software development best practices, cross-framework technical principles and critical non-technical skills that cannot be easily googled, take time to learn, are "evergreen" and have a huge impact on engineer's performance. These are significantly better at reflecting the real value a software developer / engineer brings to an organization or team.

This repository is a derivative work of the following article: "[What Makes a Great Software Engineer](https://www.romenrg.com/blog/2018/12/29/what-makes-a-great-software-engineer)".

_This is a work in progress. Important knowledge might be missing, existing bullets can probably be improved and better grouping strategies could be found. For those reasons, any contributions (i.e. PRs or issues) are welcome._ Please feel free to propose changes following [the contributing guideline](CONTRIBUTING.md).

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
    - [Programming principles](#programming-principles)
    - [Data structures](#data-structures) 
    - [Clean code](#clean-code)
    - [Source code management](#source-code-management)
    - [Technical collaboration](#technical-collaboration)
    - [DevOps practices](#devops-practices)
    - [Other general technical knowledge](#other-general-technical-knowledge)
      - [Language-theory knowledge](#language-theory-knowledge)
      - [Optimization](#optimization)
      - [Concurrency](#concurrency)   
  - [Field-specific technical knowledge](#field-specific-technical-knowledge)
    - [Front-end development](#front-end-development)
    - [Back-end development](#back-end-development)
    - [Architecture](#architecture)
    - [Infrastructure](#infrastructure)
    - [Security](#security)

## Non-technical skills

The following non-technical skills are probably the most critical for an engineer to have. Being successful as a software engineer in a company becomes very hard without good communication, teamwork attitude, development-process knowledge, problem-solving skills and a learning mindset; despite the technical skills one may have.

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
* Be constructive

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
* [Lateral Thinking](https://en.wikipedia.org/wiki/Lateral_thinking)
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

There is evergreen technical knowledge that is relevant for any software engineer, despite the specific area in which they are going to be working on. To get a good understanding of their seniority and learn how solid their engineering practices are, you can keep a conversation with them on programming principles, data structures, clean code, source code management, technical collaboration and/or DevOps practices. If these foundations are solid, they will probably be able to learn the specifics needed for your particular case without problems. 

#### Programming principles

 * Basic [control structures](https://en.wikipedia.org/wiki/Control_flow) and [boolean algebra](https://en.wikipedia.org/wiki/Boolean_algebra)
 * OOP (Object Oriented Programming)
 * [SOLID](https://en.wikipedia.org/wiki/SOLID), [GRASP](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
 * Functional programming (pure functions, immutability, recursion,...)
 * [Declarative vs Imperative programming](http://amzotti.github.io/programming%20paradigms/2015/02/13/what-is-the-difference-between-procedural-function-imperative-and-declarative-programming-paradigms/)

#### Data structures

 * Basic structures (basic types, array, matrix, object...)
 * Caching / memoization
 * Hash codes, tokens, encodings (e.g. Base64)
 * [Stack vs heap](https://stackoverflow.com/a/80113/1213497) memory

#### Clean code

 * Acknowledge that naming is key to code readability (files, classes, variables / attributes, functions / methods...)
 * Avoid long functions and classes, making sure to split responsibilities properly into methods/functions and/or classes/files
 * Follow conventions to organize project structure
 * Extract complex boolean conditions into well-named functions
 * Try to write code that is as self-explanatory as possible (i.e. "what" the code does is easy to understand by reading it)
 * Favor good naming and lightweight documentation over inline comments
     * [Code comments often lie](https://www.codeproject.com/Articles/872073/Code-Comments-are-Lies) and are usually shortcuts written to explain what a messy code block does, instead of investing the time in refactoring it to improve its readability
 * Write documentation as code, ideally alongside code, for easier maintenance (e.g. markdown files in a "docs" folder in your repository)
 * Use docs to describe "whys" and "hows" (e.g. goals, use cases, components, high-level architecture overview,...)
 * In OOP, favor [composition over inheritance](https://en.wikipedia.org/wiki/Composition_over_inheritance)
 * Follow [semantic versioning](https://semver.org/)
 * Know about TDD and its practices (e.g. "red, green, refactor")

#### Source code management

 * CVS (Control Version Systems) / SCM (Source Code Management) basics: branches, tags, centralized vs de-centralized,...
 * SCM vs repository management / hosting (i. e. [difference between Git and GitHub](https://stackoverflow.com/a/13321586))
 * Understand why versioning is important
 * Commit best practices
   * [Micro commits](https://lucasr.org/2011/01/29/micro-commits/) / atomic commits, good descriptions...)
   * [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
 * Feature branches (short-lived)
 * Trunk-based development
 * Dependency management (the importance of package managers, the risks of [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell),...)

#### Technical collaboration

* [Peer Code Review best practices](https://blog.github.com/2015-01-21-how-to-write-the-perfect-pull-request/)
    * TL;DR: Focus on the relevant pieces when performing code-reviews. The purpose is learning, not blaming.
* [Pair Programming best practices](https://martinfowler.com/articles/on-pair-programming.html)

#### DevOps practices

 * Build automation
 * Artifact repositories and image registries
 * Write automated tests
 * Differences between unit, integration and end-to-end (e2e) tests
 * Test pyramid
 * Continuous Integration
 * [Continuous Delivery vs Deployment](https://www.romenrg.com/blog/2017/12/31/continuous-integration-delivery-deployment/)
 * Feature Flags / Feature Toggles
 
#### Other general technical knowledge 

##### Language-theory knowledge

 * Regular expressions (regex)
 * Compiled vs interpreted languages
 * [Dynamic vs static & weak vs strong](https://medium.com/@cpave3/understanding-types-static-vs-dynamic-strong-vs-weak-88a4e1f0ed5f) language typing

##### Optimization

 * Lazy loading
 * [Profiling](https://en.wikipedia.org/wiki/Profiling_(computer_programming))

##### Concurrency

 * Race condition
 * Deadlock
 * Mutual exclusion

### Field-specific technical knowledge

In some cases, you may want an engineer to know about certain fields or areas already, such as front-end, back-end, architecture, infrastructure or security. In those cases, there are also cross-framework concepts and principles that can be used to drive conversations on technical knowledge that is specific to each one of those fields.

#### Front-end development

 * API communication (different architecture standards, how data is transmitted...)
 * DOM (definition, understanding, virtual DOM...)
 * Browser events
 * Responsive design (purpose, advantages, progressive enhancement...)
 * Client-side rendering (CSR) vs server-side rendering (SSR)
 * Pagination
 * State management (associated problems, stateless approach...)
 * MVC and derivatives
 * WebSockets

#### Back-end development

 * API design (different architecture standards, how data is transmitted...)
 * [Message brokers](https://en.wikipedia.org/wiki/Message_broker)
 * Relational databases (how they work, basic concepts...)
 * Non-relational databases
 * Database design
 * ORM
 * Batch processes / Cron jobs
 * Session handling
 * [Error Handling, Auditing and Logging](https://lti.umuc.edu/contentadaptor/topics/byid/db0a8c4f-f738-4674-9f60-b75323cdb07f)

#### Architecture

 * API
   * Standards: REST / SOAP
   * Security (e.g. blocking bots, controlling account take-over attacks, etc.)
   * Resiliency on 3rd-party service failures (e.g. Circuit Breakers)
 * Externalized Configuration
 * [Everything as code (i.e. Configuration as code, Infrastructure as code, Docs as code,...)](https://www.romenrg.com/blog/2019/12/31/everything-as-code/)
 * Monolith vs Microservices
 * Domain-Driven Design (DDD)
 * Hexagonal Architecture
 * Service Mesh
 * Relevant internet protocols and their usage (i.e. HTTP, HTTPS, TCP, UDP, LDAP, SSH, SMTP,...)
 * [Data modeling](https://en.wikipedia.org/wiki/Data_modeling)
 
 #### Infrastructure
 
 * Virtual machines vs Containers
 * Processes vs threads
 * Controller-agent / Primary-replica pattern
 * Client-server pattern
 * IAAS, PAAS, SASS
 * Web servers
 * Reverse proxies
 * Load balancing
 * Redundancy
 * Latency
 * Monitoring
 * [Observability](https://docs.honeycomb.io/learning-about-observability/intro-to-observability/)

#### Security

  * Identity and Access Management (IAM)
    * Authentication (JWT, SSO)
    * Authorization (RBAC, ABAC)
 * Public-key cryptosystems (e.g. RSA)
 * Cryptographic protocols (TLS, SSL)
 * Principle of least privilege
 * DoS / DDoS
 * SQL injection
 * Man-in-the-middle attack
 * XSS and CSRF

---

_This work, by [Romén Rodríguez-Gil](https://www.romenrg.com/about/), is released under the terms specified in [this license file](LICENSE) (MIT License)._
