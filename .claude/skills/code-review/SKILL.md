---
name: code-review
description: Review commercial web projects for bugs, responsive issues, unnecessary complexity and production readiness.
---

# Code Review

Review the implementation before considering a commercial website finished.

The goal is to identify real problems that could affect users, the client or future maintenance.

## Review priority

Check issues in this order:

1. Critical bugs
2. Broken functionality
3. Responsive problems
4. User experience problems
5. Performance problems
6. Maintainability problems
7. Minor improvements

Do not focus on cosmetic preferences when there are functional problems.

## Functionality

Check for:

- broken imports
- undefined variables
- runtime errors
- broken links
- incorrect routes
- non-working buttons
- broken forms
- incorrect state handling
- missing assets
- incorrect external links
- console errors

## Responsive behavior

Check:

- desktop
- tablet
- mobile
- horizontal overflow
- overlapping elements
- broken grids
- incorrect spacing
- text clipping
- buttons becoming too small
- navigation problems
- images overflowing or stretching

## UI and UX

Check:

- visual hierarchy
- readability
- button clarity
- navigation
- form usability
- typography
- spacing
- consistency
- mobile usability
- important calls to action

Do not recommend redesigning working elements without a meaningful reason.

## Accessibility

Check basic accessibility:

- semantic HTML
- button semantics
- form labels
- image alt text
- keyboard usability
- visible focus states
- sufficient text readability
- meaningful link text

## Performance

Look for obvious performance problems:

- unnecessarily large images
- excessive JavaScript
- unnecessary dependencies
- duplicated requests
- unnecessary rendering
- assets loaded when they are not needed

Do not optimize prematurely.

Prioritize measurable or obvious problems.

## Code quality

Look for:

- duplicated code
- dead code
- unused imports
- unnecessary components
- unnecessary abstractions
- confusing naming
- excessive complexity

Do not rewrite working code simply because another architecture could be used.

## Commercial website checks

For business websites also verify:

- contact information
- phone links
- WhatsApp links
- booking actions when present
- address
- opening hours
- menu
- important calls to action

Do not invent missing information.

## Final verification

Before declaring the project finished:

1. Run the project.
2. Check for errors.
3. Test the main user flows.
4. Check responsive layouts.
5. Check important links.
6. Check forms and buttons.
7. Check images.
8. Check console errors.
9. Review the final UI.

## Review output

When reporting the review, organize findings as:

### Critical
Problems that must be fixed before delivery.

### Important
Problems that should be fixed before delivery when possible.

### Minor
Small improvements that do not block delivery.

### Passed
Important areas that were checked and have no meaningful issues.

Do not invent problems.

If the project has no meaningful issues, clearly state that it is ready for delivery.
