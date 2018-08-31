## Template: ResearchProject

First of all, you have to adjust the information in the ```Settings.tex```. There you define the title and author of the work and so on. Then the files in the ```Assets``` and ```Content``` folders have to be adapted or filled with content.

You have to compile the ```ResearchProject.tex``` to let generate the pdf file.

## Folder Structure

- **Appendix/** - Contains all appendix files (name scheme: ```<nn>_appendix.tex``` - e.g. ```01_appendix.tex```)

- **Assets/** - Contains miscellaneous files e.g. cover, abstract, glossary, ...

- **Content/** - Contains all content files

  - **Figures/** - Contains all figures

  - **Listings/** - Contains all listings
    
  - **Analysis/** - Contains all analysis files 
    (name scheme: ```<nn>_analysis.tex``` - e.g. ```01_analysis.tex```)

  - **Conception/** - Contains all conception files 
    (name scheme: ```<nn>_conception.tex``` - e.g. ```01_conception.tex```)

  - **Implementation/** - Contains all analysis files 
    (name scheme: ```<nn>_implementation.tex``` - e.g. ```01_implementation.tex```)

  - **Theory/** - Contains all theory files 
    (name scheme: ```<nn>_theory.tex``` - e.g. ```01_theory.tex```)
  
  - **Introduction.tex** - File for the introduction of the topic/problem/purpose
  
  - **Background.tex** - File for the explanation of the problem
  
  - **Purpose.tex** - File  for the explanation of the purpose
  
  - **Conclusion.tex** - File for the summary

- **metadata/** - Contains all files generated during PDF building

- **CustomCommands.tex** - File in which user-defined commands can be defined

- **references.bib** - File with all references

- **ResearchProject.tex** - Main file that integrates everything

- **Settings.tex** - Defines e.g. the mandatory information on the cover sheet
