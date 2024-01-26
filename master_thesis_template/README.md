# Master Thesis Template
This repository contains a LaTeX template for a master thesis. The template is provided by [Mr. Florian Mayer](https://www.fh-joanneum.at/hochschule/person/florian-mayer/) and was slightly modified by me. The template is based on the [IEEEtran](https://www.ctan.org/pkg/ieeetran) document class and the [IEEEtran BibTeX](https://www.ctan.org/pkg/ieeetran) style file. The template is provided without any warranty. Feel free to use it for your own master thesis.

## Purpose
The template provided by Mr. Mayer is a good foundation for a master thesis, as it allows for writing a clean, professional, and well-structured document. It has many useful features, such as a title page, a table of contents, a list of figures, a list of tables, a bibliography, a glossary and more. A lot of styling is already done, so that the user can focus on the content of the thesis. Additionally, it offers many examples on how to include various elements into the document. However, I found the template, especially because of the amount of examples, slightly overwhelming and confusing. This why I decided to modify the template, to be ready for a more straightforward usage.

## Contents

Folders:
- [.idea](.idea): Configuration files for JetBrains IDE.
- [bib](bib): Bibliography files for references and citations.
- [Chapters](Chapters): Your thesis chapters go here. Edit or add new chapters as needed.
- [code](code): Source code files that are part of or referenced in the thesis.
- [figures](figures): Images and graphics used throughout the thesis.
- [frontmatter](frontmatter): Preliminary pages of the thesis, like the title page, acknowledgements, and abstract.
- [tables](tables): Separate files for tables to be included in the thesis.
- [temp_graphics](temp_graphics): Temporary or placeholder graphics files.

Files:
- [IEEEtran.bst](IEEEtran.bst): The BibTeX style file for formatting the bibliography.
- [IEEtypes.sty](IEEtypes.sty): Style definitions for the document.
- [IEEconfig.sty](IEEconfig.sty): Configuration file for IEEEtran class customization. Costumize the style of the document here.
- [main.tex](main.tex): The main LaTeX file that you compile to create your thesis.


## Usage
To use the template for your document:

1. Customize [tpThesis.tex](./frontmatter/tpThesis.tex) with your personal data.
1. Modify [loadfrontmatter.tex](./frontmatter/loadFrontmatter.tex) to suit your front matter preferences.
1. Write the necessary front matter sections within the corresponding files in the [frontmatter folder](frontmatter).
1. Write your thesis chapters in the 'chapters' folder.
1. Include these chapters into the [main](main.tex) document.
1. Remove/uncomment the example chapter provided from [main.tex](main.tex).
1. Develop your own bibliography file, similar to [ECE_tempBib.bib](./bib/ECE_tempBib.bib) for citations.
1. Modify the document to your preferences.

To create the content for your chapters, refer to the 'Example' chapter in the template. It provides straightforward examples for:

- Structuring the text into chapters, sections, and subsections.
- Using various font styles like bold and italic.
- Creating lists.
- Adding images, tables, equations, and code listings.
- Making references to different elements within your document.
