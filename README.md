# Energy and AI — Contribution Guide

Welcome to the **Energy and AI** Quarto Book project! This README will help you get started, even if you have never used GitHub or contributed to a documentation project before.

---

## 📋 Table of Contents

1. [Prerequisites](#prerequisites)  
2. [Getting the Code (Clone)](#getting-the-code-clone)  
3. [Running & Previewing the Book](#running--previewing-the-book)  
4. [Making Changes](#making-changes)  
5. [Committing & Pushing](#committing--pushing)  
6. [Creating a Pull Request](#creating-a-pull-request)  
7. [Style & Formatting Guidelines](#style--formatting-guidelines)  
8. [Need Help?](#need-help)  

---

## 🚀 Prerequisites

Before you begin, make sure you have the following installed on your computer:

- **Git**: Version control tool. https://git-scm.com/downloads  
- **Quarto**: For rendering the book. https://quarto.org/docs/get-started/  
- **A text editor or IDE** (e.g., VS Code, RStudio, or your favorite editor).  

---

## 📥 Getting the Code (Clone)

1. Go to the project’s GitHub page:  
   `https://github.com/Corne173/Energy-and-AI`  
2. Click **Code** → **HTTPS** → **Copy** the URL.  
3. Open a terminal and run:

   ```bash
   git clone https://github.com/Corne173/Energy-and-AI.git
   cd Energy-and-AI
   ```

---

## 🔍 Running & Previewing the Book

Inside the project folder, run:

```bash
quarto preview
```

- Starts a local web server.  
- Open your browser to the printed address (e.g., `http://localhost:4200`) to see the book live.  
- **Save** any `.qmd` or `.ipynb` changes and **refresh** the page to update.  

---

## ✏️ Making Changes

1. **Create a new branch** for your work:

   ```bash
   git checkout -b my-feature-branch
   ```

2. **Add or edit content**:  
   - New chapters: create a file like `new-section.qmd` in the `source/` folder.  
   - Edit existing files under `source/`.

3. **Preview** your changes locally:

   ```bash
   quarto preview
   ```

---

## ✅ Committing & Pushing

Once you’re happy with your changes:

```bash
git add .
git commit -m "Describe your change succinctly"
git push origin my-feature-branch
```

---

## 📬 Creating a Pull Request

1. Go to the GitHub repo in your browser.  
2. Click **Compare & pull request** for your branch.  
3. Fill in:
   - **Title**: Brief summary of your changes.  
   - **Description**: More details, screenshots, or context.  
4. Click **Create pull request**.  

---

## 📐 Style & Formatting Guidelines

- **YAML front matter** at the top of each `.qmd`:

  ```yaml
  ---
  title: "Your Chapter Title"
  format: html
  ---
  ```

- **Headings**: Use `#` for chapter titles, `##` for sections.  
- **Citations**: Add sources to `references.bib` and cite with `[@citationKey]`.  
- **Images**: Place in `source/images/` and reference with `![](images/your-image.png)`.  

---

## 🤝 Need Help?

If you run into any problems or have questions:

- Open an **Issue** on GitHub describing the problem.  
- Ask a maintainer or leave a comment on your Pull Request.  

Thank you for contributing! 🎉
