# DVA Group Project Writeups - Team 55

This overleaf project / Github repository contains files for our writeups - including proposal, progress report, final report. Link to the [Overleaf Page](https://www.overleaf.com/project/6597a11521d727340d7dbdca), the [Github Repository](https://github.com/ZebraAlgebra/dva-project-writeups).

The specifications are given [here](https://docs.google.com/document/u/0/d/e/2PACX-1vSlYrMw402tL3F95ay-AaptTdF80UOER-gne_O0kqbuuk6WXrlsjwaYjjS0Jyl95dXYyDLjh9DR1mln/pub?pli=1).

## FAQs

### How to compile the document?

Use options `pdfLaTeX`, with main document set to `main.tex`.

Depending on your editor, there are some slightly different ways of doing so. Overleaf and most other editors have GUIs or shortcut keys for configuring the compilation process.

If you prefer to work on your local machine more than on Overleaf, you may clone this repo and pull the changes when needed:

```
git clone https://github.com/ZebraAlgebra/dva-project-writeups
```

### Where are packages configured?

They are managed in `metadata.sty`. Some global configs (document headers, where to search for other tex files) are also in it.

### Where to edit the contents of the document?

Go to `./src/$docSrc/$sectionTag.tex`. For example, to edit project proposals' literature review section, go to `./src/proposal/literatures.tex`.

### How are references managed?

They are given as `.bib` files in the `./ref/` directory, specified as bibtex entries. After adding the entries, use the `/ref` command to cite the reference.

[Google Scholar](https://scholar.google.com/) can be used to automatically generate bibtex entries if Google can find it. One can also refer to the [bibtex website](https://www.bibtex.com/e/entry-types/) and manually fill in the necessary info.
