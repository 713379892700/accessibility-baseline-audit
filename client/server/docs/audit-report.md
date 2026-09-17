# Accessibility Audit Report

## Audited Website
Amazon.in

## Lighthouse Score
Accessibility: 92

## Findings

### WEB-003: ARIA attributes do not match their roles
- WCAG: 4.1.2 Name, Role, Value
- Severity: Medium
- Evidence: Lighthouse report
- User impact: Screen reader users may receive incorrect information.
- Recommendation: Ensure ARIA attributes match the element's role.

### WEB-004: Touch targets
- WCAG: 2.5.8 Target Size
- Severity: Medium
- Evidence: Lighthouse report
- User impact: Users may have difficulty activating small touch targets.
- Recommendation: Increase touch target size and spacing.

### WEB-005: Heading order
- WCAG: 1.3.1 Info and Relationships
- Severity: Medium
- Evidence: Lighthouse report
- User impact: Screen reader users may have difficulty understanding page structure.
- Recommendation: Use headings in a logical order.

### WEB-006: Image alt text
- WCAG: 1.1.1 Non-text Content
- Severity: Low
- Evidence: Lighthouse report
- User impact: Screen reader users may receive unnecessary descriptions.
- Recommendation: Remove redundant alt text.
