# GitHub Wiki Sidebar and Footer Guide

This guide explains how to create and maintain navigation sidebar and footer for your GitHub Wiki.

## Sidebar Setup

### Step 1: Create Sidebar File

Create a file named exactly `_Sidebar.md` in your wiki repository's root. This special filename is required for GitHub to recognize it as the sidebar.

### Step 2: Basic Sidebar Structure

Here's a recommended sidebar structure:

```markdown
### Wiki Navigation

* [📚 Home](home)
* [⚙️ Setup](setup-home)
  * [Installation](setup-installation)
  * [Configuration](setup-configuration)
  * [Dependencies](setup-dependencies)
* [📖 Documentation](docs-home)
  * [API Reference](docs-api)
  * [Database Schema](docs-database)
  * [Architecture](docs-architecture)
* [🔧 Development](dev-home)
  * [Getting Started](dev-getting-started)
  * [Code Style](dev-code-style)
  * [Testing](dev-testing)
* [📝 Guidelines](guidelines-home)
  * [Contributing](guidelines-contributing)
  * [Code Review](guidelines-code-review)
  * [Release Process](guidelines-release)

---

* [🔗 Repository](https://github.com/your-org/your-repo)
* [🐞 Issue Tracker](https://github.com/your-org/your-repo/issues)
* [📋 Project Board](https://github.com/your-org/your-repo/projects)
```

### Step 3: Enhanced Sidebar Example

Here's a more detailed sidebar with categories and status indicators:

```markdown
### 📚 Project Wiki

#### 🚀 Getting Started
* [Welcome Guide](welcome)
* [Quick Start](quick-start)
* [FAQ](faq)

#### 💻 Development
* [Setup Development Environment](dev-setup)
* [Architecture Overview](dev-architecture)
* [Code Guidelines](dev-guidelines)
  * [JavaScript Style Guide](dev-js-style)
  * [Python Style Guide](dev-python-style)
  * [Git Workflow](dev-git-workflow)

#### 🔧 API Documentation
* [API Overview](api-overview)
* [Authentication](api-auth)
* [Endpoints](api-endpoints)
* [Error Codes](api-errors)

#### 📦 Deployment
* [Deployment Guide](deploy-guide)
* [Configuration](deploy-config)
* [Monitoring](deploy-monitoring)

#### 🧪 Testing
* [Testing Strategy](test-strategy)
* [Unit Tests](test-unit)
* [Integration Tests](test-integration)

---

#### 🔗 Quick Links
* [Repository](https://github.com/your-org/your-repo)
* [Issues](https://github.com/your-org/your-repo/issues)
* [Releases](https://github.com/your-org/your-repo/releases)

#### 📊 Project Status
* [🟢 Production](https://your-app.com)
* [🟡 Staging](https://staging.your-app.com)
* [🔵 Development](https://dev.your-app.com)
```

## Footer Setup

### Step 1: Create Footer File

Create a file named exactly `_Footer.md` in your wiki repository's root.

### Step 2: Footer Examples

#### Basic Footer:
```markdown
---
[Home](home) • [Documentation](docs) • [Support](support) • [Contributing](contributing)  
© 2024 Your Organization. [Terms](terms) • [Privacy](privacy)
```

#### Enhanced Footer:
```markdown
---
#### Quick Access
[📚 Docs](docs) • [💬 Discussions](discussions) • [🐞 Issues](issues) • [📋 Projects](projects)

#### Status & Links
[![Build Status](build-badge-url)](build-url) • [![Coverage](coverage-badge-url)](coverage-url)

#### Connect
[GitHub](github-url) • [Discord](discord-url) • [Twitter](twitter-url)

---
*Last updated: YYYY-MM-DD • [Report an issue](issues/new) • [Edit this page](edit)*  
© 2024 Your Organization. All rights reserved.
```

## Best Practices

1. **Sidebar Organization**
   - Use emojis for visual hierarchy
   - Group related items under categories
   - Keep nesting to maximum 2-3 levels
   - Use consistent naming conventions

2. **Footer Design**
   - Keep it minimal and informative
   - Include essential links only
   - Add version or last updated info
   - Consider adding status badges

3. **Maintenance**
   - Update links regularly
   - Check for broken links
   - Keep the structure consistent
   - Remove outdated sections

## Tips for Navigation

1. **Use Clear Categories**
   - Group similar content
   - Use descriptive names
   - Maintain logical order

2. **Visual Hierarchy**
   - Use headings for sections
   - Add separators between groups
   - Include icons/emojis for visual cues

3. **Link Management**
   - Use relative paths for internal links
   - Test all links after updates
   - Keep external links up to date

## Common Issues and Solutions

1. **Sidebar Not Showing**
   - Verify file is named exactly `_Sidebar.md`
   - Ensure file is in repository root
   - Check file permissions

2. **Footer Not Appearing**
   - Confirm file is named exactly `_Footer.md`
   - Place file in repository root
   - Validate markdown syntax

3. **Broken Links**
   - Use relative paths correctly
   - Update links after page moves
   - Regular link validation

---

**Note**: Remember to commit and push your `_Sidebar.md` and `_Footer.md` files to see changes on GitHub Wiki.