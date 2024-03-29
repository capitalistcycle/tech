# tech
Technology Testing and Familiarization for Models and Publications

## pandemic

Start immediately with Atom editor and pandemic to focus on content.

https://lionel-rigoux.github.io/pandemic/tutorial/

Output to LaTeX and tweak with TeXstudio:

pandemic publish manuscript.md --format tex

Default goes straight to pdf. Others include html and docx (and pandoc can do pretty well anything)

Use a scaffoold that includes this header in the template:

---
pandemic:

format: tex
  
---

Change styles with recipes:

https://lionel-rigoux.github.io/pandemic/recipes/

Template also includes header for bibtex files:

---
bibliography:
  - myReferences.bib
  - ../shared/references.bib
---

Data from yaml or json can be templated into content using mustache:

https://mustache.github.io/mustache.5.html

Also includes pandoc-crossref to number equations, figures, tables:

https://lierdakil.github.io/pandoc-crossref/#syntax

There is also work in progress for extracting and converting images:

https://github.com/lionel-rigoux/pandemic-image

Much more powerful integration with JupyterLab etc and additional enhancements and integration using other tools below.

An alternative is pandocomatic:

https://github.com/htdebeer/pandocomatic

That may be more powerful with a better support ecosystem but it should be easier to learn how to use it by starting with pandemic first.

There is also a vast ecosystem of other pandoc related projects.

## pandoctools

https://github.com/kiwi0fruit/pandoctools

https://github.com/kiwi0fruit/pandoctools/tree/master/docs

https://github.com/kiwi0fruit/pandoctools/blob/master/docs/atom.md

https://github.com/kiwi0fruit/pandoctools/blob/master/docs/best_python_jupyter_pycharm_experience.md

https://github.com/kiwi0fruit/pandoctools/blob/master/docs/atom_jupyter_pandoc_markdown.md

See also other tools from same author:

https://github.com/kiwi0fruit/misc

## pandoc filters

http://scorreia.com/software/panflute/

https://github.com/kiwi0fruit/pandoctools/blob/master/docs/panfl.md

## sugartex

https://github.com/kiwi0fruit/sugartex/blob/master/sugartex.md

Hopefully can include most simple maths without using TeXstudio.

Examples in this folder:

This pdf file shows example of the raw markdown code that can be easily edited with Atom together with rendered pdf:

https://github.com/capitalistcycle/tech/blob/master/examples.pdf

The markdown file is:

example.md - there may be some trick to make it look better on GitHub

The LaTeX generated file is:

example.md.md - this is unreadable


## TeXstudio

Needed for publisher templates, complex maths and final WYSIWYG tweaking before producing pdf or html etc from markdown. Also helps to learn some minimal LaTeX by seeing the output from SugarTeX and markdown.

May also use TeXmacs for instant rendering of maths and integration with Sage etc. 

