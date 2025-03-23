# Guide to Using GitHub Wiki with `.md` Files and Images

## 1. Linking to `.md` Files

When using GitHub Wiki, there are certain limitations when referencing and organizing `.md` files:

- **No differentiation of subdirectories**: GitHub Wiki **does not differentiate subdirectories**. If you place `.md` files within subfolders, links to these files will automatically be **flattened**, and only files at the **root level** of the Wiki repository will be recognized.

### Example

Suppose you have the following directory structure:

```arduino
├── install/
│   ├── install-0home.md
```

- When linking to the file `install-0home.md`, you **only need to use the file name**, without specifying the subdirectory.

**Correct linking:**

```markdown
[home](install-0home)
```

GitHub Wiki will automatically recognize the `install-0home.md` file in the `install/` folder without needing to specify the full path.

> IMPORTANT
>
> - This behavior is specific to GitHub Wiki.
> - When creating links, avoid using **/folder** or including the **.md** extension, as they will not be recognized by GitHub Wiki.
>   - Incorrect
>     - `[home](install/install-0home.md)`
>     - `[home](install/install-0home)`
>     - `[home](install/0home)`
>   - Correct: `[home](install-0home)`

## 2. Linking to Images

GitHub Wiki uses a simple mechanism for linking images within `.md` files:

- **No subdirectory differentiation for images:** If you create an `image/` directory anywhere in the repository, GitHub Wiki will only recognize the image via a simple path, like `image/filename.png`, regardless of where the directory is located in the repository.

### Example

Suppose you have the following directory structure:

```arduino
├── docs/
│   ├── guide.md
├── image/
│   ├── logo.png
```

Here, `guide.md` is the `.md` file where you want to link the image `logo.png` from the `image/` folder.
When linking to the image in `guide.md`, you **only need to use the simple path** to the image file, without specifying the subdirectory.

**Correct linking:**

```markdown
![Logo](image/logo.png)
```

GitHub Wiki will automatically recognize the image, even if the `image/` folder is located outside the root of the Wiki or in a subdirectory.

## Summary

- **GitHub Wiki does not differentiate subdirectories** for `.md` file links. The paths will be automatically flattened, and you only need to reference the file name without specifying the directory path.
- **When linking to images**, GitHub Wiki will automatically recognize the image based on a simple path, regardless of the folder's location within the repository.
