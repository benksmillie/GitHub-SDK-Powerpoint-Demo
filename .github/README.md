# Designer Agent Configuration

This directory contains the configuration for the **Primer Designer Agent**, an AI assistant that ensures all code follows the Primer Design System guidelines.

## Files

- **`copilot-instructions.md`**: Comprehensive Primer Design System guidelines for GitHub Copilot
- **`copilot-agents.json`**: Agent configuration that automatically reviews code for Primer compliance
- **`designer-agent.yml`**: GitHub Actions workflow for automated design system checks

## How It Works

### 1. Copilot Instructions
The `copilot-instructions.md` file provides context to GitHub Copilot about:
- Primer component usage patterns
- Accessibility requirements
- Typography and layout guidelines
- Code quality standards

### 2. Designer Agent
The Primer Designer Agent (`copilot-agents.json`) automatically:
- Reviews UI code files (`.jsx`, `.tsx`, `.css`, `.html`)
- Suggests Primer components instead of custom implementations
- Validates accessibility compliance
- Checks heading hierarchy and semantic HTML
- Provides specific feedback with Primer documentation links

### 3. Automated Checks
The GitHub Actions workflow (`designer-agent.yml`) runs on every PR to:
- Check for Primer component usage
- Validate accessibility requirements
- Comment on PRs with compliance results

## Usage

When writing UI code, the Designer Agent will automatically:
- Suggest Primer components as you type
- Flag non-compliant code patterns
- Provide Primer-specific recommendations
- Link to relevant documentation

## Quick Reference

**Always use Primer components:**
- `Button` instead of custom buttons
- `Heading` instead of raw HTML headings
- `Avatar` for user/org representations
- `NavList` for side navigation
- `Spinner` for loading states
- `Label` for tags and metadata

**Key principles:**
- Accessibility first
- Semantic HTML
- Consistent design tokens
- Mobile-first responsive design

For full guidelines, see `copilot-instructions.md` and visit [primer.style](https://primer.style/)
