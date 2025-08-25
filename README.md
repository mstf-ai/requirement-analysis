## 📘 What is Requirement Analysis?

**Requirement Analysis** is the disciplined process of discovering, clarifying, documenting, and validating what a software system must do and under what constraints it must operate. It turns stakeholder needs and business objectives into clear, testable, and prioritized **requirements** that guide design, implementation, and verification.

### Why It Matters in the SDLC
- **Reduces rework & cost:** Fixing a misunderstanding early is far cheaper than changing code late in the lifecycle.
- **Aligns stakeholders:** Creates a shared, unambiguous understanding of scope and success criteria.
- **Guides architecture & design:** Functional needs and quality attributes (e.g., performance, security) shape technical choices.
- **Enables testability:** Well-written requirements become the basis for acceptance tests and QA plans.
- **Controls scope:** A baselined set of requirements plus change control prevents scope creep.

### Goals
- Capture *what* the system must do (not *how*).
- Elicit both **functional** and **non-functional** (quality) requirements.
- Resolve conflicts, close gaps, and remove ambiguity.
- Prioritize requirements to deliver maximum value early.

### Inputs & Outputs
- **Inputs:** Business goals, current workflows, regulations, stakeholder interviews, existing systems.
- **Outputs:**  
  - **SRS** (Software Requirements Specification) or Product Requirements Document  
  - **Use cases / user stories** with acceptance criteria  
  - **Glossary**, **scope statement**, **assumptions/constraints**  
  - **Traceability matrix** (linking requirements → design → tests)

### Core Activities
1. **Elicitation:** Interviews, workshops, observation, document analysis, surveys, prototyping.
2. **Analysis & Modeling:** Use cases, user stories, data models, state diagrams, workflows.
3. **Specification:** Write clear, consistent, testable requirements (avoid ambiguous terms like “fast,” “user-friendly”).
4. **Validation & Verification:** Stakeholder reviews, prototypes, and feasibility checks to ensure the “right” requirements are captured and are implementable.
5. **Prioritization & Baselining:** Rank (e.g., MoSCoW: Must/Should/Could/Won’t) and establish a baseline with change control.
6. **Traceability Management:** Maintain links from requirements to design artifacts, code, and tests.

### Types of Requirements
- **Functional:** Behaviors or capabilities (e.g., “A guest can book a property for selected dates.”)
- **Non-Functional (Quality Attributes):** Performance, security, availability, usability, accessibility, compliance (e.g., “Search results return within 300 ms for 95% of requests.”)
- **Constraints:** Technology, regulatory, budget, timeline (e.g., “Use PostgreSQL,” “GDPR compliance.”)

### Writing Good Requirements (Checklist)
- **Clear & unambiguous:** Single interpretation.
- **Atomic:** One requirement = one need.
- **Testable:** Has measurable acceptance criteria.
- **Necessary & feasible:** Supports a goal and can be built.
- **Consistent:** No conflicts with others.
- **Traceable:** Has a unique ID and links to tests/design.

**Example (User Story + Acceptance Criteria):**  
- *As a guest, I want to filter properties by price range so that I can find stays within my budget.*  
  - Given the listings page, when I set a minimum and maximum price and click Apply, then only properties with nightly price within that range are shown.  
  - If no results match, a friendly “No results” message is displayed.

### Common Pitfalls & How to Avoid Them
- **Vague terms** → Replace with measurable criteria.
- **Jumping to solutions** → Focus on *what* before *how*.
- **Missing stakeholders** → Map roles early; include operations, compliance, and support.
- **Scope creep** → Baseline + change control.
- **Poor prioritization** → Use MoSCoW/WSJF to maximize value delivery.

### Deliverables in This Repo
- `/docs/SRS.md` — detailed specification and glossary  
- `/docs/use-cases/` — use cases & user stories with acceptance criteria  
- `/docs/traceability.md` — matrix linking requirements → design → tests

> **Bottom line:** Requirement Analysis is the bridge between business intent and working software. Doing it well accelerates delivery, improves quality, and reduces risk across the SDLC.
---
## 🌟 Why is Requirement Analysis Important?

Requirement Analysis is one of the most critical phases of the Software Development Life Cycle (SDLC). Without it, projects risk failing due to unclear goals, wasted resources, and unmet stakeholder expectations. Below are key reasons why Requirement Analysis is essential:

1. **Prevents Misunderstandings and Rework**  
   By clearly defining what the system must do, Requirement Analysis eliminates ambiguity and ensures all stakeholders share the same vision. This reduces costly rework caused by unclear or misunderstood requirements later in development.

2. **Guides Design and Development**  
   Requirements act as a blueprint for developers, architects, and testers. Well-defined requirements provide clarity on scope and functionality, ensuring that design decisions and implementation efforts align with business goals.

3. **Improves Quality and Testability**  
   Clear, testable requirements allow QA teams to design accurate test cases and validation checks. This ensures the final product meets user needs, complies with standards, and delivers expected performance.

4. **Manages Scope and Resources Effectively**  
   Requirement Analysis helps control scope creep by setting boundaries and prioritizing features. This ensures that time, budget, and resources are allocated efficiently to deliver maximum value.

5. **Strengthens Stakeholder Alignment**  
   Involving stakeholders in the requirement analysis process builds trust and alignment. It ensures their needs are properly captured, validated, and agreed upon before development begins.

> **In summary:** Requirement Analysis is the foundation for project success. It ensures the right product is built, within budget and time, while meeting stakeholder expectations.

