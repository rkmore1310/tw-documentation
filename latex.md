# LaTeX – Document Preparation System

## What is LaTeX?
LaTeX is a document preparation system widely used in academia and research to create clean, well-formatted reports, papers, and technical manuals[cite: 10]. Instead of manually adjusting fonts and spacing like in a regular word processor, you write plain text with simple formatting tags, and LaTeX handles the layout automatically.

## Key Concepts Learned in Class
- **Document Structure:** Every LaTeX file starts with `\documentclass{article}` (or `report`/`book`) and places the main content inside `\begin{document}` and `\end{document}`.
- **Sections & Formatting:** Easy organization using `\section{}`, `\subsection{}`, `\textbf{}` for bold, and `\textit{}` for italics.
- **Mathematical Equations:** LaTeX makes writing complex math formulas simple using inline math (`$...$`) or display math (`$$...$$`).
- **Tables & Figures:** Inserting images with `\includegraphics` and organizing data cleanly using the `tabular` environment.
- **Compilation:** Converting `.tex` source files into a polished `.pdf` document (while ignoring temporary build files like `.aux` and `.log` in Git)[cite: 29].

## Why It Is Useful
It keeps formatting consistent across long documents, handles numbering and references automatically, and works great with Git because `.tex` files are plain text.