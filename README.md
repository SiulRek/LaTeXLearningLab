# LaTeXLearningLab

This repository is dedicated to my journey in learning LaTeX. This repository contains a collection of LaTeX projects, each focusing on different aspects and features of LaTeX.

## Purpose

The purpose of this repository is to provide example and template documents that can be used to learn LaTeX. The examples range from basic documents to more structured and styled templates. Each, here mentioned, folder contains a specific LaTeX project (document) with its own README.md with descriptions. Feel free to explore these projects to get started with LaTeX and understand the basic LaTeX capabilities.

## Repository Contents

- **First Document**: An introductory LaTeX document, showing basic structuring and formatting.
  - [First Document README](first_document/README.md)
- **Second Document**: A simple LaTeX document, similar to the first document.
  - [Second Document README](second_document/README.md)
- **Third Document**: More complex LaTeX document with a modular folder structure.
  - [Third Document README](third_document/README.md)
- **Report Template**: A comprehensive LaTeX report template demonstrating custom styling and advanced features.
  - [Report Template README](report_template/README.md)
- **Presentation Template**: A Beamer presentation template, highlighting various presentation elements in LaTeX.
  - [Presentation Template README](presentation_template/README.md)
- **Master Thesis Template**: A LaTeX template provided by Mayer Florian and slightly changed for simplified usage by me for writing the master's thesis. 
  - [Master Thesis Template README](master_thesis_template/README.md)
- **Real Documents Folder**: Contains a collection of real documents I have created.
  - [Real Documents Folder](real_documents/)
- **Feature Demos Folder**: This folder contains a collection of documents demonstrating some LaTeX features like glossary, indexing, language_support.
  - [Feature Demos Folder](feature_demos/)

## Getting Started with LaTeX


For those new to LaTeX, navigating LaTeX might initially feel a bit complex, especially understanding its engines, packages, and structure. A helpful resource for getting started is the [LaTeX Workshop for mac](https://www.youtube.com/watch?v=CmagZthwhaY) or the [LaTeX Workshop for windows](https://www.youtube.com/watch?v=4lyHIQl4VM8&t=227s) of Federi Tartarini. This tutorial offers an easy-to-follow guide on setting up the LaTeX environment. Remember, the sequence in which you install components is important – I've faced issues due to installation order myself. Also, debugging in LaTeX can be a bit challenging since error messages aren’t always clear. In such cases, the .log file, GitHub Copilot and ChatGPT, can be quite useful.

## About LaTeX

### Basic Principles of LaTeX
- **Typesetting System** LaTeX is a typesetting system ideal for structured documents, particularly those with mathematical content. It extends TeX, a foundational typesetting system.
- **Compiled Nature**: Unlike word processors, LaTeX documents are written in plain text files and then compiled into a formatted document, typically PDF.
- **TeX Engine**: LaTeX uses a TeX engine in the background for compilation, transforming the text and commands into a high-quality document.

### LaTeX Commands and Environments
- **Commands** in LaTeX start with a backslash `\` and can include required `{}` and optional `[]` arguments.
- **Environments**, marked by `\begin` and `\end`, define document sections with specific behavior, like `figure` or `table`.
- **Comments**: In LaTeX, line comments start with `%`, allowing annotations or deactivation of code without execution.

### Command Examples
LaTeX provides a variety of commands and macros for customizing and enhancing document design. Here are a few examples:

- **Font Styles**: LaTeX offers commands like `\textbf` for bold text, `\textit` for italic text, and `\texttt` for monospaced text.
- **Mathematical Symbols**: LaTeX provides commands for mathematical symbols, such as `\alpha` for α, `\beta` for β, and `\sum` for ∑.
- **Lists**: LaTeX offers commands for creating different types of lists, such as `\itemize` for bullet points and `\enumerate` for numbered lists.
- **Tables**: LaTeX provides commands for creating tables, such as `\begin{tabular}` and `\end{tabular}`, allowing you to define the structure and content of the table.
- **Figures**: LaTeX offers commands for including figures, such as `\includegraphics`, allowing you to insert images into your document.
- **Custom Commands**: LaTeX provides the `\newcommand` macro for creating custom commands, streamlining complex tasks and enhancing document design flexibility.

These are just a few examples of the many commands and macros available in LaTeX. They allow you to customize various aspects of your document and create complex structures with ease.

### Definitions
- **TeX Primitives** are low-level, foundational commands in TeX for tasks like setting fonts and defining dimensions.
- **LaTeX Macros** are higher-level commands, often consisting of TeX primitives, designed for ease of use, like the commands mentioned in the previous section.
- **Custom macros** are created using `\newcommand`, streamlining complex tasks and enhancing document creation efficiency.

### Understanding the Interplay of Tex Primitives and LaTeX Macros
- LaTeX abstracts the complexity of TeX primitives into user-friendly macros, making it more accessible while retaining the power of TeX for advanced users.

### Packages in LaTeX
- Packages in LaTeX are collections of additional commands and features that extend the functionality of LaTeX.
- They are included in a document using the `\usepackage` command.
- Packages cover a wide range of functionalities, such as adding graphics, formatting tables, or typesetting mathematical equations.
- Popular packages include `graphicx`, `amsmath`, and `hyperref`.
- Note: When including a package in LaTeX, it may come with default settings that can change the page layout or font style, providing a predefined configuration!


This overview provides insights into LaTeX's command structure, custom command creation, and the role of environments and macros, showcasing the system's versatility for document creation.