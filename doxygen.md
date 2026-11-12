# Doxygen – Automated Code Documentation

## What is Doxygen?
Doxygen is a documentation generator tool that reads special comments written inside source code and automatically turns them into clean, organized documentation (such as HTML web pages or LaTeX/PDF manuals).

## Key Concepts Learned in Class
- **Special Comment Blocks:** Writing structured comments directly above functions, classes, and files (for example, using `///` or `/** ... */` in C/C++).
- **Documentation Tags:** Using simple tags inside comments to describe code clearly:
  - `@brief` – A short summary of what a function or file does.
  - `@param` – Describes each input parameter of a function.
  - `@return` – Explains what value the function returns.
- **Configuration File (`Doxyfile`):** Generating a `Doxyfile` using `doxygen -g` to customize project name, input folders, and output formats.
- **Generating Output:** Running `doxygen Doxyfile` to build the complete documentation automatically.

## Why It Is Useful
It keeps documentation right next to the code, making it easy to update whenever the code changes and helping other developers understand a project quickly.