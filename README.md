# Evergreen Skills for Software Developers
This repository includes a list of "evergreen skills" that should serve as a fair assessment of skilled software developers / engineers.

The purpose of this work is to serve as an alternative resource for conducting hiring interviews of software developers / engineers. This document focuses on software development best practices, cross-framework principles and other portable skills; instead of the usual focus on trends and/or specific knowledge of short-lived frameworks, which tend to quickly become outdated and often don't reflect the real value software developers / engineers bring to the organization.

This repository is a derivative work of the following article: "[What Makes a Great Software Engineer](https://www.romenrg.com/blog/2018/12/29/what-makes-a-great-software-engineer)".

_This is a work in progress. Important knowledge might be missing, existing bullets can probably be improved and better grouping strategies could be found. For those reasons, any contributions (i.e. PRs) are welcome._ Please feel free to propose changes following [the contributing guideline](CONTRIBUTING.md).

## Table of contents

- [Core skills](#core-skills-aka-soft-skills)
  - [Communication](#communication)
  - [Teamwork](#teamwork)
  - [Technical collaboration](#technical-collaboration)
- [Innovation & (self-)management skills](#innovation--self-management-skills)
  - [Development process](#development-process)
  - [Problem solving skills](#problem-solving-skills)
  - [Mindset](#mindset)
- [Technical skills](#technical-skills)
  - [General technical knowledge](#general-technical-knowledge)
    - [Principles](#principles)
    - [Clean Code](#clean-code)
    - [Collaboration and SCM](#collaboration-and-SCM)
    - [DevOps practices](#devops-practices)
  - [Field-specific technical knowledge](#field-specific-technical-knowledge)
    - [Front-end development](#front-end-development)
    - [Back-end development](#back-end-development)
    - [Architecture](#architecture--infrastructure)
    - [Security](#security)
    - [Scaling & optimization](#scaling--optimization)
    - [Concurrency](#concurrency)


## Core Skills (aka "soft" skills)

### Communication

* Follow e-mail best practices
* Follow chat best practices
* Minimize interruptions
* Be polite

### Teamwork

* Keep low egos
* Be an active listener
* Be a good mentor
* Share knowledge
* Engage in constructive decisions

### Technical collaboration
* [Pull Request Best Practices](https://blog.github.com/2015-01-21-how-to-write-the-perfect-pull-request/)
* Focus on the relevant pieces when performing code-reviews
* Pair programming best practices

## Innovation & (self-)management skills

### Development process

* Comfortable with iterative and incremental development
* Self-organizing capability
* Avoid creating false expectations
* Focus on priorities and business value

### Problem solving skills

* [5 Whys](http://en.wikipedia.org/wiki/5_Whys)

### Mindset

* Don't fear change
* Dare to fail
* Be a life-long learner
* Be rational: question decisions, "let the facts do the talking"

## Technical skills

### General Technical Knowledge

#### Principles
 * OOP
 * SOLID, GRASP
 * Functional programming (pure function, recursion,...)
 * Cache, memoization
 * Hash code, tokens, encondings (eg Base64)
 * Data structures (basic types, array, matrix, object...)

#### Clean code
 * Self-explainatory code
 * Use good naming (for files, variables, classes, functions...)
 * Avoid long functions and classes ()
 * Extract complex boolean conditions into functions
 * Use lightway documentation instead of inline-comments

#### Collaboration and SCM
 * CVS / SCM knowledge
 * Why is versioning important
 * Commits best practices (atomic commits, good descriptions...)
 * Feature branches / feature toggles
 * Trunk-based development

#### "DevOps" practices
 * Write automated tests
 * Differences between unit, integration and system tests
 * Test pyramid
 * Continuous Integration
 * Continuous Delivery vs Deployment

### Field-specific technical knowledge

#### Front-end development
 * DOM (definition, understanding, virtual DOM...)
 * Responsive design (purpose, advantages, progresive enhancement...)
 * API standards: REST / SOAP
 * State management (associated problems, stateless approach...)
 * MVC and derivatives
 * Websockets

#### Back-end development
 * Relational databases (how do they work, basic artifacts...)
 * Batch processes / Cron Jobs
 * Database design
 * ORM
 * Session handling

#### Architecture & Infrastructure
 * Externalized Configuration
 * Infrastructure as code
 * Microservices
 * Virtual machines vs Container
 * Master-slate pattern
 * Client-server pattern
 * IAAS, PAAS, SASS

#### Security
 * Public-key cryptosystems (e.g. RSA)
 * Principle of least privilege
 * DoS / DDoS
 * SQL injection
 * Man-in-the-middle attack
 * XSS and CSRF

#### Scaling & optimization
 * Load balancing
 * Redundancy
 * Latency

#### Concurrency
 * Race condition
 * Deadlock
 * Mutual exlusion

---

_This work is released under the terms specified in [this license file](LICENSE), based on MIT License._
