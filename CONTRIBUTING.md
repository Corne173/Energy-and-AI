
# Contributing to the "Energy and AI" Quarto Book

Thank you for your interest in contributing! This document provides guidelines to help you get started.

## 📋 How to Contribute

### For the Repository Owner (or Maintainers)

1. Clone the repository:
   ```bash
   git clone https://github.com/Corne173/Energy-and-AI.git
   cd Energy-and-AI
   ```

2. Create a new branch for your changes:
   ```bash
   git checkout -b update-topic-x
   ```

3. Edit the relevant `.qmd` file or add a new one.

4. Preview your changes locally:
   ```bash
   quarto preview
   ```

5. Stage and commit your changes:
   ```bash
   git add .
   git commit -m "Added new section on XYZ"
   git push --set-upstream origin update-topic-x
   ```

6. Open a Pull Request (PR) on GitHub and merge after review.

### For External Contributors

1. **Fork** the repository on GitHub.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Energy-and-AI.git
   cd Energy-and-AI
   ```

3. Create a new branch:
   ```bash
   git checkout -b my-contribution
   ```

4. Make your changes and preview them:
   ```bash
   quarto preview
   ```

5. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Descriptive message about your contribution"
   git push origin my-contribution
   ```

6. Go to your fork on GitHub and click **Compare & Pull Request** to submit your changes.

## ✍️ Content Guidelines

- Use `.qmd` files for your chapters/sections.
- Maintain consistency in tone and style.
- Use clear section headers and keep formatting clean.
- Reference any external material properly in the `references.bib` file.

## 🧪 Testing

Use `quarto preview` to check the output locally before submitting your contribution.

## ❓ Questions

If you have questions, please open an issue or contact the maintainer.
