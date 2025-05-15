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

   - Replace my-feature-branch with a descriptive name (e.g., `gang-edits` or `sakhile-ai-chapter`). This command creates a new branch and switches to it.
   This command only needs to be run once. You'll make all your changes on this branch. Later, this branch can be merged into the main branch so everyone’s work comes together.

2. **Add or edit content**:  
   - **To add a new chapter:** Create a new `.qmd` file (e.g., `my-topic.qmd`) in the main project folder. Use the template below to get started:
     ```yaml
     ---
     title: "Chapter Title"
     format: html
     ---
     # Chapter Title

     Your content here.
     ```
   - **To edit existing content:** Open any of the `.qmd` files (such as , , etc.) in your editor and make your changes.
   - **Add images:** Place images in an `images/` folder (create it if it doesn't exist) and reference them in your `.qmd` files with `![](images/your-image.png)`.
   - **Cite sources:** Add references to  and cite them in your text using `[@citationKey]`.

**Tip:** To view your changes, you first have to stop the previous preview by pressing `Ctrl + C` in the terminal. Then, run `quarto preview` again to see your changes.

---

## ✅ Committing & Pushing

Once you’re happy with your changes, you need to save them to GitHub.  
You can do this using **either the terminal or the VS Code interface**:

---

### Option 1: Using the Terminal

```bash
git add .
git commit -m "Describe your change succinctly"
git push origin my-feature-branch
```

---

### Option 2: Using VS Code (No Terminal Needed)

1. **Open the Source Control panel**  
   Click the Source Control icon (the branch icon) on the left sidebar.

2. **Stage your changes**  
   - You’ll see a list of changed files.  
   - Click the **+** icon next to each file, or click the **+** at the top to stage all.

3. **Commit your changes**  
   - Enter a short description in the message box (e.g., “Add new chapter on AI in energy”).  
   - Click the **checkmark** (✔) button to commit.

4. **Push your branch to GitHub**  
   - Click the **…** (More Actions) menu at the top of the Source Control panel.  
   - Select **Push** (or **Push to...** if prompted).


Now your changes are saved to your branch on GitHub! Next you can create a Pull Request to merge your changes into the main branch.

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
