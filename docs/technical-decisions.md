\# Technical Decisions



\## Decision Log



\### 2026-06-03 — Use Figma for Wireframing and UI/UX Design



\*\*Status:\*\* Decided



\*\*Options Considered\*\*



\* Figma

\* Framer

\* Webflow

\* Direct implementation



\*\*Why / Tradeoffs\*\*

Figma provides a free tier, strong industry adoption, and allows low-fidelity wireframes before implementation. It separates design from coding and encourages iterative feedback.



\*\*Impact\*\*

Initial design work will be created in Figma before implementation in code.



\---



\### 2026-06-03 — Determine Whether Portfolio Website Requires a Database



\*\*Status:\*\* Deferred



\*\*Options Considered\*\*



\* No database

\* File-based content

\* Relational database



\*\*Why / Tradeoffs\*\*

Current MVP only needs static content and downloadable resume files. A database adds complexity and maintenance and can be revisited after MVP completion.



\*\*Impact\*\*

The MVP will proceed without a database. Future versions may introduce one if dynamic content management becomes necessary.



\---



\### 2026-06-03 — Limit MVP to Home, About, Experience, and Contact Pages



\*\*Status:\*\* Decided



\*\*Options Considered\*\*



\* Full portfolio

\* Simplified MVP



\*\*Why / Tradeoffs\*\*

A smaller scope increases the likelihood of completion and allows earlier stakeholder feedback.



\*\*Impact\*\*

Initial development focuses on four pages before expanding to projects and resume enhancements.



\---



\### 2026-06-05 — Defer Java + Spring Boot for MVP



\*\*Status:\*\* Decided / Deferred



\*\*Options Considered\*\*



\* Java + Spring Boot application

\* Plain HTML/CSS/JavaScript

\* Modern frontend framework/library

\* Static site approach



\*\*Why / Tradeoffs\*\*

\*\*Why / Tradeoffs\*\*

Feedback from Code Club RDU suggested that Java + Spring Boot introduces additional complexity without solving a current MVP requirement. Since the website primarily contains static content, navigation, project information, and professional contact links, a frontend-first approach better aligns with the project's immediate goals.



\*\*Impact\*\*

MVP development will focus on frontend implementation and user experience. Spring Boot may be revisited later if backend features become necessary.





\## Version History



| Version | Date | Notes |

|----------|----------|----------|

| 1.0 | 2026-06-03 | Initial technical decisions documented. |

| 1.1 | 2026-06-05 | Updated following Code Club RDU feedback regarding MVP scope and architecture. |

