## Creating Wiki Sidebar

The sidebar provides quick navigation across your Wiki pages. To create one:

1. Create a file named `_Sidebar.md` in your Wiki repository root
2. Add navigation links using Markdown syntax
3. Commit and push the changes

### Example Sidebar Structure

```markdown
### Wiki Navigation

* [Home](home)
* [Installation](install-0home)
  * [Clone Repository](install-clone)
  * [Create Pages](install-create)
  * [Push Changes](install-push)
* [Usage](usage-0home)
  * [Markdown Guide](usage-markdown)
  * [Images](usage-images)
  * [Links](usage-link)
```

> ⚠️ **Note**: The sidebar file must be named exactly `_Sidebar.md` to be recognized by GitHub Wiki.
