# Clean code principles to always follow

## Separation of concerns
Each module or component should handle one specific responsibility.
Changes in one concern have minimal impact on others (low coupling, high cohesion). Teams can work in parallel on different modules without stepping on each other’s toes.
**Why it matters**: code is easier to read, test, and modify.
**Example**: the MVC (Model View Controller) design pattern.
Avoid deeply nested blocks, always prefer refactoring into functions.

## Don't Repeat Yourself (DRY)
Focus on reducing redundancy across the codebase — not only in code, but also in logic, data, and documentation.
Centralize shared logic or configuration to avoid inconsistencies.
Use abstraction or utilities to remove duplication where appropriate.
**Why it matters**: Duplication makes maintenance harder and increases the chance of errors when requirements change or if one variable has to be updated in multiple places.
**Example**: Instead of copying the same validation logic across multiple modules, define it in one function and reuse it.

## Keep it Super Simple! (KISS)
Focuses on avoiding unnecessary complexity. Simplicity should be a core design goal — avoid unnecessary complexity or overengineering.
Prefer clarity over cleverness.
Don’t use advanced abstractions or patterns when a simple conditional or loop works.
Write code that a new developer can understand quickly.
**Why it matters**: Simple code is easier to debug, maintain, and evolve. Complexity adds risk without always adding value, it slows development, and makes future changes harder.
**Example**: Don’t use advanced abstractions if a straightforward loop and conditional will do. Avoid introducing multiple design patterns just to solve a simple data flow issue.

# Before taking architectural decisions
When multiple best practices or design options are valid:
Always use ask_followup_question to clarify which approach fits best.
Provide context about trade-offs, scalability, maintainability, and performance implications.
The goal is informed choice, not rigid adherence.
