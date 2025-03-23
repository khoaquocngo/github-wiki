# Create and Organize Wiki Pages

This guide shows how to create Markdown pages, embed images, and organize files for a clean and efficient GitHub Wiki.

---

## Step 1: Open Wiki Repository in Editor

- Open the cloned Wiki folder in your preferred code editor (e.g., VS Code, PyCharm).
- Example folder: `<repository>.wiki/`  
  ![Open in editor](images/1742616533896.png)

---

## Step 2: Create Markdown Files

- Each `.md` file becomes a separate Wiki page on GitHub.
- Example: `home.md`, `Installation.md`, `Usage.md`  
  ![Create new file](images/1742616533897.png)

---

### Organize with Folders (Optional)

- For clarity, group related `.md` files into folders.

    ```text
    <repository>.wiki/
    ├── home
    ├── install/
    │   ├── install-0home.md
    │   ├── install-clone.md
    │   └── install-create.md
    ├── usage/
    │   └── usage-0home.md
    │   └── usage-markdown.md
    ├── images/
    │   └── images-0home.png
    │   └── images-setup.png
    ```

> ⚠️ **Note**: GitHub Wiki does not show folders—use relative links for navigation.

## Step 3: Write Content in Markdown

- Use **Markdown** syntax to format your Wiki page.

### Example Content

```markdown
# Installation Guide

This guide helps you set up the project locally.

## Steps

1. Clone the repository
2. Install dependencies
3. Run the application
```

  ![View write content](images/1742616533898.png)
