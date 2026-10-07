---
name: frontend-engineering
description: Build and maintain production-quality React and TypeScript code for the JON PASCUAI portfolio. Use this skill whenever creating, modifying, refactoring, debugging, or reviewing frontend code.
---

# Frontend Engineering

## Purpose

Build a production-quality frontend for the JON PASCUAI personal portfolio.

The implementation should prioritize:

1. Maintainability
2. Accessibility
3. Performance
4. Type safety
5. Responsive design
6. Reusability
7. Visual consistency

Do not over-engineer simple functionality.

---

## Technology stack

The project uses:

- React
- TypeScript
- Vite
- Tailwind CSS
- ESLint
- Lucide React
- Motion

Do not introduce another library unless there is a clear technical
reason to do so.

Before adding a dependency, evaluate whether the existing stack
already provides an appropriate solution.

---

## React architecture

Use functional React components.

Prefer small, focused components.

A component should have a clear responsibility.

Avoid:

- huge components
- deeply nested components
- duplicated UI
- unnecessary abstraction
- unnecessary state
- unnecessary effects

If a component becomes difficult to understand, consider splitting it.

---

## TypeScript

Use TypeScript strictly.

Prefer explicit types for:

- component props
- data structures
- reusable functions
- external data
- configuration objects

Avoid:

`any`

Do not use type assertions to hide real type problems.

Prefer solving the underlying typing issue.

Use interfaces or type aliases consistently.

---

## Component design

Components should be:

- reusable
- predictable
- composable
- easy to understand

Prefer composition over complex conditional components.

Example:

```tsx
<ProjectCard project={project} />