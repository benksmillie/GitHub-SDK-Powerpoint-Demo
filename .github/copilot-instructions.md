# GitHub Copilot Instructions

## Primer Design System Guidelines

Follow the [Primer Design System](https://primer.style/) guidelines for all UI development work.

### General Principles

- **Use Primer Components**: Always prefer Primer components over custom implementations
- **Accessibility First**: Ensure all UI components meet accessibility standards
- **Consistent Styling**: Follow Primer's design tokens for colors, spacing, typography
- **Responsive Design**: Use Primer's responsive utilities for mobile-first development

### Component Usage

#### Buttons
- Use `Button` for actions (e.g., in forms)
- Use `Link` for navigation/destinations
- Use `IconButton` for icon-only buttons
- Always include appropriate button variants: `primary`, `secondary`, `danger`, `invisible`

#### Navigation
- Use `NavList` for side navigation
- Use `UnderlineNav` for tabbed navigation with underlined selected state
- Use `Breadcrumbs` to display page hierarchy

#### Layout
- Use `Box` as a basic wrapper for layout needs
- Apply consistent spacing using Primer spacing scale
- Follow responsive breakpoints from Primer

#### Forms
- Use `AutoComplete` for search/suggestion inputs
- Use `TextInput`, `Select`, and other form components from Primer
- Always include proper labels and error states

#### Feedback & Status
- Use `Spinner` for loading states
- Use `ProgressBar` to visualize task completion
- Use `Label` for contextual metadata
- Use `State` for status indicators
- Use `Blankslate` for empty states

#### Typography
- Use `Heading` (h1-h6) for page hierarchy
- Use `Text` wrapper for typography styles
- Use `Truncate` for overflowing text
- Don't use headings for styling alone

#### Other Components
- Use `Avatar` for users (circle) and organizations (square)
- Use `AvatarStack` to stack multiple avatars
- Use `Counter` for counts on navigation/buttons
- Use `Popover` for contextual UI guidance
- Use `TimelineItem` for vertical timelines
- Use `ClipboardCopyButton` for copy-to-clipboard functionality

### Code Quality

- Write semantic HTML
- Use proper ARIA labels and roles
- Test with keyboard navigation
- Ensure color contrast meets WCAG standards
- Write component tests for custom implementations

### Resources

- [Primer Components](https://primer.style/components)
- [Primer Design Tokens](https://primer.style/foundations/primitives)
- [Primer React](https://primer.style/react)
- [Primer CSS](https://primer.style/css)
- [Primer View Components (Rails)](https://primer.style/view-components)

