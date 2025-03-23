# Table of Contents in GitHub Wiki

This guide shows how to create a manual Table of Contents (ToC) for your Wiki pages to help users navigate easily.

---

## Why Use a Table of Contents?

GitHub Wiki does not automatically generate ToCs for multiple pages. Adding a manual ToC improves organization and discoverability.

---

## Create a ToC in `home`

- Structure your Wiki homepage with links to major sections and pages.

```markdown
# 📖 Table of Contents

- [Installation](install-home)
  - [Clone the Repository](install-clone)
  - [Create Wiki Page](install-create)
  - [Push Changes](install-push)
- [Usage](usage-home)
  - [Markdown Syntax](usage-markdown)
  - [Embed Images](usage-images)
  - [Link Pages](usage-link)
  - [Table of Contents](usage-toc)
```

> ⚠️ **Note**: Use correct relative paths based on folder structure.

---

## Tips for Managing ToCs

- Use bullet points and indentation for clarity.
- Keep link text short and meaningful.
- Update the ToC whenever new pages are added.

---

## Example Screenshot

```md
![Example ToC](usage-home)
```

> ✅ **Tip**: Add anchor links within a single page using `[#section-name]` to navigate quickly to sections.
