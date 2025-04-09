# GitHub Wiki Guidelines

This document outlines the naming conventions and folder structure guidelines for our GitHub Wiki pages.

## Naming Conventions

### Page Names

- Use PascalCase for all wiki page names
- Prefix pages with appropriate categories
- Use hyphens (-) to separate concepts within the same category
- Examples:
  - `Development-CodeReview`
  - `Setup-LocalEnvironment`
  - `API-Authentication`
  - `Testing-UnitTests`

### Categories

Main categories should be used as prefixes:
- `Development-*`: Development-related guidelines
- `Setup-*`: Setup and installation guides
- `API-*`: API documentation
- `Testing-*`: Testing-related documentation
- `Architecture-*`: System architecture documentation
- `Operations-*`: Operations and deployment guides

## Folder Structure

```
wiki/
├── assets/                     # Store all images and attachments
│   ├── images/                # Screenshots and diagrams
│   ├── diagrams/              # Architecture and flow diagrams
│   └── documents/             # PDF and other documents
│
├── development/               # Development documentation
│   ├── guidelines/           # Coding standards and guidelines
│   ├── workflows/            # Development workflows
│   └── best-practices/       # Best practices documentation
│
├── setup/                     # Setup documentation
│   ├── environment/          # Environment setup guides
│   └── tools/                # Development tools setup
│
├── api/                      # API documentation
│   ├── endpoints/            # API endpoints documentation
│   ├── authentication/       # Auth-related documentation
│   └── examples/             # API usage examples
│
└── operations/               # Operations documentation
    ├── deployment/           # Deployment guides
    ├── monitoring/           # Monitoring setup and guidelines
    └── maintenance/          # Maintenance procedures
```

## File Naming Rules

1. Use lowercase for all folder names
2. Use hyphens (-) to separate words in folder names
3. Use descriptive names that clearly indicate content
4. Keep names concise but meaningful

## Content Guidelines

### Images
- Store all images in `assets/images/`
- Use descriptive names: `feature-workflow-diagram.png`
- Maximum size: 1MB per image
- Preferred formats: PNG, JPEG, SVG

### Links
- Use relative links when linking between wiki pages
- Use absolute links for external resources
- Always check for broken links before committing

### Markdown Usage
- Use proper heading hierarchy (H1 -> H6)
- Include a table of contents for long pages
- Use code blocks with appropriate language tags
- Use tables for structured data
- Use bullet points for lists
- Use numbered lists for sequential steps

## Best Practices

1. **Keep Pages Focused**
   - One topic per page
   - Break long pages into logical sub-pages

2. **Regular Updates**
   - Review content quarterly
   - Update documentation when related code changes
   - Mark outdated content

3. **Version Control**
   - Include last updated date
   - Maintain change log for significant updates
   - Reference related pull requests when applicable

4. **Navigation**
   - Maintain a clear hierarchy
   - Include breadcrumbs for deep pages
   - Link related pages

## Example Page Template

```markdown
# Feature Name

Last Updated: YYYY-MM-DD

## Overview
Brief description of the feature/topic

## Prerequisites
- Requirement 1
- Requirement 2

## Steps
1. First step
2. Second step
3. Third step

## Related Pages
- [Related Page 1](./Related-Page-1)
- [Related Page 2](./Related-Page-2)

## References
- [External Reference 1](https://example.com)
- [External Reference 2](https://example.com)
```

## Getting Started

1. Clone the wiki repository
2. Create new pages following the naming conventions
3. Organize content according to the folder structure
4. Add images and attachments to appropriate asset folders
5. Update the sidebar navigation when adding new pages

## Questions and Support

For questions about these guidelines or wiki management:
1. Open an issue in the repository
2. Tag it with 'documentation'
3. Assign to the documentation team

---

**Note**: These guidelines should evolve with the project. Suggest improvements by creating issues or pull requests.