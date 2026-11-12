# Beamer – Presentations in LaTeX

## What is Beamer?
Beamer is a LaTeX document class used to create clean, professional presentation slides. Just like regular LaTeX documents, you write your slide content in plain text and compile it into a PDF presentation.

## Key Concepts Learned in Class
- **Document Class:** Presentations use `\documentclass{beamer}` instead of `article`.
- **Creating Slides (Frames):** Each individual slide is wrapped inside a `\begin{frame}{Slide Title}` and `\end{frame}` block.
- **Themes:** You can change the entire look, color scheme, and layout of your presentation with a single command like `\usetheme{Madrid}` or `\usetheme{Berlin}`.
- **Bullet Points & Blocks:** Using `itemize` for bullet points and `block` environments to highlight important definitions or formulas.
- **Step-by-Step Reveals:** Using `\pause` to reveal bullet points one by one during a live presentation.

## Why It Is Useful
It allows you to reuse equations, tables, and formatting directly from your LaTeX reports without taking screenshots or retyping formulas.