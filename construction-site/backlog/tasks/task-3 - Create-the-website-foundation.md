---
id: TASK-3
title: Create the website foundation
status: To Do
assignee: []
created_date: '2026-10-04 22:19'
labels: []
dependencies:
  - TASK-2
ordinal: 3000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Establish the smallest maintainable technical foundation for the construction-business website before any production page or content implementation begins. Approved baseline architecture: Vite; semantic HTML5; modern CSS; vanilla JavaScript; npm; Zoo as the agent harness; the existing shared Zoo configuration at the workspace dev/.zoo level. React or another frontend framework is not part of the baseline. Scope: initialize the project with the Vite vanilla template; establish a simple and obvious file/folder structure; add only necessary project-level Zoo guidance; make the reusable web-design/accessibility/frontend-quality skills available to the project as appropriate within the existing Zoo setup; add minimal formatting configuration; establish CSS custom properties for the small approved design system from TASK-2; confirm the development server works; confirm the production build works. Strict dependency-minimization rule: the desired initial production dependency count is zero; any additional dependency requires a concrete demonstrated requirement and human approval. Explicitly out of scope: React, Vue, Svelte, Angular, Tailwind, Bootstrap, jQuery, component libraries, animation libraries, CMS integration, analytics, backend work, and actual production page/content implementation beyond what is necessary to verify the foundation.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 The vanilla Vite project starts and serves with npm run dev
- [ ] #2 npm run build succeeds
- [ ] #3 No frontend framework (React, Vue, Svelte, Angular) is installed
- [ ] #4 No unnecessary production dependencies exist; initial production dependency count is zero
- [ ] #5 The file/folder structure is small and understandable
- [ ] #6 Zoo can operate on the repo through the existing shared harness at dev/.zoo
- [ ] #7 Minimal formatting configuration is in place
- [ ] #8 CSS custom properties for the approved design system are established
- [ ] #9 The project is ready for the actual site implementation task
<!-- AC:END -->
