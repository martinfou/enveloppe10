---
template_version: 1.1.0
last_updated: 2026-02-16
compatible_with: [feature-request, bug-fix, product-backlog]
requires: [markdown-support]
---

# Sprint 4: Font Selection

[← Back to Product Backlog](../backlog/product-backlog.md)

**Sprint ID**: SPR-004  
**Start Date**: 2026-02-16  
**End Date**: 2026-03-02  
**Sprint Review Date**: 2026-02-16  
**Sprint Retrospective Date**: 2026-02-16  
**Overall Status**: ✅ Completed

## Sprint Overview

The goal of this sprint is to provide users with more customization options by allowing them to select between different font styles for their envelopes. 

## Sprint Goals

1.  **Typography Selection**: Implement a system to switch between Serif, Sans-Serif, and Handwriting fonts.
2.  **Visual Continuity**: Ensure the font selection carries over perfectly to the printed output.
3.  **Persistence**: Remember the user's font choice across sessions.

## User Stories / Features

| ID | Title | Priority | Points | Status |
|----|-------|----------|--------|--------|
| [FR-009](../backlog/features/FR-009-font-selection.md) | Font Selection | 🔴 Critical | 2 | ✅ Completed |

## Acceptance Criteria

- [x] A font selection dropdown is available in the UI.
- [x] At least three distinct font styles are supported in preview and print.
- [x] UI feedback is instant when selecting a font.
- [x] Selected font is saved to `localStorage`.

## Sprint Summary

The font selection feature adds a necessary layer of customization to the app. Using Google Fonts via CDN allowed for high-quality typography without increasing the project's payload significantly. Alpine.js once again proved efficient for managing UI state and persistence.

## Sprint Retrospective

- **What went well?**
  - Smooth integration of external fonts.
  - The use of buttons instead of a dropdown made the font switcher very accessible and easy to use.
- **What could be improved?**
  - Should consider local font caching or font loading states for users with slow connections.
- **Next steps?**
  - Add individual font size controls.

## Definition of Done
- All code merged to `main`.
- Site deployed to GitHub Pages.
- Sprint document updated with status and retrospective notes.
