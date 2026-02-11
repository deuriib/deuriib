---
applyTo: '**'
---

# Project Handover: deuriib

## Overview

This repository serves as a professional profile and portfolio for Deuri Vasquez, Co-Founder & Head of Technology at Mintoria. It primarily contains documentation showcasing expertise in fintech, backend architecture, and cloud infrastructure.

**Maintainer:** Deuri Vasquez
**Expertise:** C# .NET, Node.js, Angular, Azure, Web3, AI Architecture
**Primary Documentation:** README.md (professional background and contact details)

---

## Current Status

- **Repository Type:** Documentation/Portfolio (no source code)
- **Build System:** None (static markdown)
- **Package Manager:** None
- **Test Suite:** None

---

## Build, Lint, and Test Commands

Since this is a documentation-only repository with no build artifacts or source code, standard build/test commands do not apply. However, for documentation maintenance:

### Markdown Validation

```bash
# Validate markdown syntax (if markdownlint is available)
npx markdownlint-cli README.md

# Check for broken links (if lychee is available)
lychee README.md

# Preview markdown rendering
npx markdown-preview README.md
```

### Git Operations

```bash
# Standard git workflow for documentation updates
git add README.md
git commit -m "docs: update professional profile"
git push origin master
```

---

## Code Style Guidelines

### Markdown Formatting

- Use ATX-style headers (`#` not underlines)
- Indent with 2 spaces for nested lists
- Use fenced code blocks with language identifiers
- Keep lines under 100 characters when possible
- Use semantic line breaks (one sentence per line) for version control friendliness

### Writing Style

- Prefer active voice over passive voice
- Use present tense for current roles, past tense for previous positions
- Include quantifiable achievements (metrics, percentages, user counts)
- Keep bullet points parallel in structure
- Use emoji sparingly and consistently (1-2 per section maximum)

### File Organization

- README.md: Main professional profile (keep under 100 lines)
- Images: Store in `assets/` directory (if added)
- Links: Use full URLs for external references
- Badges: Group at top of document for visibility

### Naming Conventions

- **Directories:** kebab-case (e.g., `assets/`)
- **Images:** descriptive-kebab-case.png (e.g., `project-architecture.png`)
- **Sections:** Use emoji + title format for major sections

### Link Management

- Verify all external links are accessible
- Use HTTPS for all URLs
- Include descriptive text for accessibility (avoid "click here")
- Update broken links immediately when discovered

### Version Control

- Use Conventional Commits for documentation changes:
  - `docs:` for README updates
  - `fix:` for link corrections
  - `feat:` for new sections
- Keep commits atomic (one logical change per commit)
- Never commit directly to main without review

---

## Anti-Patterns to Avoid

- **DON'T** include sensitive information (phone numbers, personal addresses)
- **DON'T** use relative links that may break on GitHub rendering
- **DON'T** commit large binary files (>1MB) to the repository
- **DON'T** use HTML in markdown unless absolutely necessary
- **DON'T** include outdated job information - keep current

---

## Future Enhancements

If this repository evolves to include:

1. **Project Code:** Add appropriate language-specific AGENTS.md sections
2. **Documentation Site:** Consider adding VitePress, Docusaurus, or similar
3. **CI/CD:** Add GitHub Actions for markdown linting and link checking
4. **Portfolio Projects:** Create separate directories with their own documentation

---

## Contact

For questions about this repository or professional inquiries:
- Email: deuriib.work@gmail.com
- LinkedIn: https://www.linkedin.com/in/deurivasquez0/
- GitHub: https://github.com/deuriib
