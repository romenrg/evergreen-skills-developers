# Changelog for Evergreen Skills for Software Developers

This file keeps a log of version releases. This file is maintained
[following best practices about changelogs](https://keepachangelog.com/en/1.0.0/).

## Versioning guideline

* Each significant change should be described in the "Unreleased" section
* Entry versions should follow the following:
  * Syntax:
    * [X.Y.Z] - YYYY-MM-DD (Short description)
  * Convention:
    * For X.Y.Z, increment the digit following this scheme:
      * X = breaking change (previous version is now deprecated),
      * Y = additive change (previous version is still valid),
      * Z = just a simple patch (for a typo or error).
* When the new version is released, a new [Unreleased] section is created in the "Release Change History" below, as a 
placeholder for the next version.

## Release Change History

### [Unreleased] [4.1.0] - 2020-12-29 ()

#### Added

* Domain-Driven Design (DDD) and Hexagonal Architecture, in Architecture
* Conventional commits, in Source Code Management
* API Security and Circuit Breakers, in Architecture

#### Changed

* Added intro for main sections: "Non-technical skills", "General technical knowledge" and "Field-specific technical knowledge"
* "Principles" to "Programming principles", in "General technical knowledge"
* Titles of all sections changed to Sentence case (also in index)
* "Engage in constructive decisions" -> "Be constructive"; in Teamwork

#### Removed

*

### [4.0.0] - 2020-12-23 (Significant additions, better introduction and grouping improvements)

#### Added

* IAM, Authentication and Authorization; under Security
* Language-theory knowledge, under a new "Other general technical knowledge" section (includes regex)
* Stack vs Heap, under Data Structures
* Non-relational databases, under back-end development
* Message brokers, under back-end development
* Pagination, under front-end development
* Cryptographic protocols (TLS, SSL), in Security
* Relevant internet protocols, in Architecture
* Service Mesh, in Architecture
* Data modeling, in Architecture
* Processes vs Threads, under Infrastructure
* Web servers and reverse proxies, under Infrastructure
* Monitoring and Observability, under Infrastructure
* Immutability, in Functional Programming, within Principles
* Client-side rendering (CSR) vs server-side rendering (SSR), in front-end development
* Browser events, under front-end development
* Profiling, under Optimization
* Artifact repositories and image registries, in DevOps practices

#### Changed

* Improved introduction to better reflect the importance of evergreen skills and portable technical knowledge
* Improved license note
* Grouped the "be rational and facts-based" entry into Critical Thinking, with link to its definition
* Renamed "master-slave" to "Controller-agent / Primary-replica"
* Improved Peer Code Review best practice adding TL;DR note
* Links for "control structures" and "boolean algebra"
* Significant improvements to Clean Code section
* Split Architecture and Infrastructure
* Monolith vs Microservices, in Architecture
* Concurrency is now part of "Other general technical knowledge"
* Replaced "system tests" with "end-to-end tests"

#### Removed

* Scaling and optimization section. Optimization is now under "Other general technical knowledge" and the scaling-related bullets are part of Infrastructure

### [3.0.0] - 2020-11-30 (Grouping tech vs non-tech skills; plus adding multiple links and style improvements)

#### Added

* Specific link on the importance of proper use of threads in chat apps
* Link on Pair Programming best practices
* Link to Agile Software Development principles
* Link on the importance of empathy
* Link to the example of time estimates on "avoid creating false expectations"
* Multiple new problem-solving skills, with links
* Links on SOLID and GRASP
* Added package managers and dependency hell to "Dependency management"
* Added link on "Continuous Delivery vs Deployment"
* Enhanced "Infrastructure as code" with configuration and docs. Added link to "Everything as code" article
* CI process running in CodeShip to perform spelling checks

#### Changed

* Top level grouping now divided between technical and non-technical skills
* Most abbreviations now have the full meaning next to them
* Links are now set as text anchors in most cases (instead of separate in parentheses as before)
* Fixed some typos
* Markup improvements: All titles have the same case (capitalized) and always a blank line afterwards
* Minor improvements to changelog and typo fixed in contributing guideline

#### Removed

* .

### [2.0.0] - 2019-01-19 (Extended sections, created new & more reference links)

#### Added

* Architecture and Infrastructure section
* Security section
* "Semantic versioning", included in the "Clean Code" section
* "Dependency management", in the "Collaboration and SCM" section
* "Control structures and Boolean algebra", into "Principles"
* "Imperative vs declarative programming", included in the principles section, with a reference article

#### Changed

* Back-end section: minor changes to existing items and added some new concepts (e.g. "session handling" and "database design")
* Split "Principles" section, creating also "Data Structures"
* Included a link to e-mail and chat (Slack) communication best practices
* Linked to article about the productivity cost of interruptions

#### Removed

* .

### [1.0.0] - 2018-12-30 (First release)

#### Added

* First draft including 3 groups of skills: core (aka "soft"), innovation & (self-)management
* Table of contents
* Introduction, purpose and work-in-progress disclaimer
* Contributing guidelines, code of conduct and templates for PRs and issues

#### Changed

* 

#### Removed

*
