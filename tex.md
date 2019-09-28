## Environment

https://sinews.siam.org/Details-Page/markdown-a-writing-tool-for-every-applied-mathematicians-toolbox

https://shd101wyy.github.io/markdown-preview-enhanced/#/

Use  this fork. See details of extra packages needed.

https://github.com/gicentre/markdown-preview-enhanced-with-litvis

https://vega.github.io/vega-lite/

https://vega.github.io/vega/docs/

https://vega.github.io/vega/docs/api/statistics/

https://vega.github.io/vega/examples/

https://guide.elm-lang.org

https://github.com/gicentre/elm-vegaLite

https://package.elm-lang.org/packages/gicentre/elm-vega/latest

https://prettier.io/docs/en/index.html


Learn LaTeX with a standard editor, the wikibook and queries at tex.stackexchange.com.

May still use TeXmacs for WYSIWYG drafting. Especially actual maths directly connected to Sage etc and very fancy scripting in Guile/Scheme Lisp dialect. Easier to export from TeXmacs to LaTex than the other way.

Will still need a normal LaTeX editor for submission to many publications and will still need to pick up raw LaTeX code while using it rather than becoming reliant on TeXmacs WYSIWYG. May need access to the extensive ecosystem of TeX including CTAN:

https://en.m.wikipedia.org/wiki/List_of_TeX_extensions

Future work will mainly use git with GFM Markdown for version control and collaborative editing, perhaps with some advanced features of LwDITA with help from Atom editor, so as to focus entirely on content. 

Zotero for references and pandoc/pandocmatic to mash with LaTeX maths (perhaps exported from TeXmacs) and usually export to LaTex for final polishing and use of specific publisher templates.

TODO. Consider standard spreadsheets or some other separate software for tables that will be compatible with Wikipedia and LwDITA. Then mash those separately from text, references and maths.

There is a script available to cut and paste tables from spreadsheets etc to TeXstudio:

https://github.com/texstudio-org/texstudio/wiki/Scripts#paste-as-latex-table

Some publishers may require Word or similar. especially for books with indexing software. Can still go via Markdown and LwDITA for those. 

Start with TeXstudio (TXS or txs) as it is an enhanced fork from Texmaker and also cross platform as picking up other features from Kile, TeXworks and TeXshop. Fully synchronized, customizable and scriptable. Understanding how a solid LaTex editor works will be helpful for learning how to mash things together and learning necessary minimum of actual LaTeX maths code for use with mathjax. Advanced features probably help with minimizing keystrokes and editing time.

It is similar enough to Texmaker to be easy to shift from that. But has many more keyboard shortcuts. Not sure if all the corresponding ones are identical but anyway better to become familiar with TeXstudio.

Reviewers overwhelmingly prefer TeXstudio here:

https://tex.stackexchange.com/questions/208219/what-are-the-main-differences-between-texmaker-and-texstudio

https://tex.stackexchange.com/questions/339/latex-editors-ides

Uses only SVN for version control but I assume no problem just running git on top as well. There is a script for it:

https://github.com/texstudio-org/texstudio/wiki/Scripts#git-commit-and-push

Powerful scripting useful for mashing:

https://github.com/texstudio-org/texstudio/wiki/Scripts

For mobile use possibly VerbTex or Anoc based on:

https://en.m.wikipedia.org/wiki/Verbosus 

Probably better to use browser based Cocalc, Authorea, Overleaf or LaTeX Online Editor on servers.

But Android Tablet should be able to run Linux editors and no real need on phone.

Quick look at comparisons did not show any reason to spend more time studying others now. 

But perhaps checkout WYSIWYM with Lyx later. Maybe closer to Markdown/LwDITA for mashing:

https://en.m.wikipedia.org/wiki/WYSIWYM

https://en.m.wikipedia.org/wiki/LyX

Also note can use Emacs (AUCTeX), Atom (with latex, latex-plus, or best with latextools together with language-latex, pdf-view and atom-project manager packages) and Eclipse (TeXlipse). Relevant if mainly working in those environments.

Checkout Atom if using it for Markdown and programming. Ditto for Eclipse.

https://en.m.wikipedia.org/wiki/Comparison_of_TeX_editors

https://en.m.wikipedia.org/wiki/Texmaker

http://texstudio.sourceforge.net/manual/current/usermanual_en.html 20pp

Joint Forum with TeXstudio:

https://latex.org/forum/viewforum.php?f=21&sid=6f9a09bb08533d0385248309df4e66ee

Open Office Dictionaries?

https://wiki.openoffice.org/wiki/Dictionaries

Tutorial: https://www.youtube.com/watch?v=7NMthqjTB1k

Initially manually convert documents done already to LaTeX and pdf.

Then switch to GFM using pandocomatic and switch to long term environments for PC and Android Tablet (and perhaps phone)

TeXstudio is a forked enhancement which should be better:

https://en.m.wikipedia.org/wiki/TeXstudio

https://www.texstudio.org

https://github.com/texstudio-org/texstudio/wiki

http://texstudio.sourceforge.net/manual/current/usermanual_en.html 29pp

Tutorial: https://www.youtube.com/watch?v=TqwgNRbd-2I

Wiki (archived)
https://web.archive.org/web/20140424192410/http://sourceforge.net/apps/mediawiki/texstudio/index.php?title=Main_Page

Comparison looks good (except need separate for Android):

https://en.m.wikipedia.org/wiki/Comparison_of_TeX_editors

Fedora Magazine has an article on using TeXstudio which mentions some of the packages.

Adding columns, images and links
Columns, images and links help add further information to your text. LaTeX includes functions for some advanced features as packages. The \usepackage command loads the package so you can make use of these features.

For example, to make an image visible, you might use the command \usepackage{graphicx}. Or, to set up columns and links, use \usepackage{multicol} and \usepackage{hyperref}, respectively.

The \includegraphics command places an image inline in your document. (For simplicity, include the graphics file in the same directory as your LaTeX source file.)

Here’s an example that uses all these concepts. It also uses two PNG graphics files that were downloaded. Try your own graphics to see how they work.

\documentclass{article} 
\usepackage{graphicx}
\usepackage{multicol}
\usepackage{hyperref}
\begin{document} 
 \textbf{GNU}
 \vspace{1cm}
 
 GNU is a recursive acronym for "GNU's Not Unix!", chosen because GNU's design is Unix-like, but differs from Unix by being free software and containing no Unix code.
 
 Richard Stallman, the founder of the project, views GNU as a "technical means to a social end". Stallman has written about "the social aspects of software and how Free Software can create community and social justice." in his "Free Society" book.
 \vspace{1cm}
 
 \textbf{Some Projects}
 
 \begin{multicols}{2}
 Fedora
 \url{https://getfedora.org}
 \includegraphics[width=1cm]{fedora.png}
 
 GNOME
 \url{https://getfedora.org}
 \includegraphics[width=1cm]{gnome.png}
 \end{multicols} 
 
\end{document}

## Packages

Lookup following packages (for document class "article"). CTAN pages have links for full pdf docs and for the package:

\usepackage{multicol}

Multicol defines a multicols environment which typesets text in multiple columns (up to a maximum of 10), and (by default) balances the end of each column at the end of the environment. The package enables you to switch between any (permitted) number of columns at will: there is no imposed “clear page” operation, as there is in unadorned LATEX at a switch between \onecolumn and \twocolumn sections. The multicolumn environment can also be used inside a box, thus allowing multicolumned insets in text.

Multicol patches the output routine, and may clash with other packages that do the same (e.g., longtable); furthermore, there is no provision for single column floats inside a multicolumn environment, so figures and tables must be coded in-line (using, for example, the H modifier of the float package).

The package is part of the latex-tools bundle in the LATEX required distribution.

https://ctan.org/pkg/multicol

\usepackage{hyperref}

The hyperref package is used to handle cross-referencing commands in LATEX to produce hypertext links in the document. The package provides backends for the \special set defined for HyperTEX DVI processors; for embedded pdfmark commands for processing by Acrobat Distiller (dvips and Y&Y’s dvipsone); for Y&Y’s dviwindo; for PDF control within pdfTEX and dvipdfm; for TEX4ht; and for VTEX’s pdf and HTML backends.

The package is distributed with the backref and nameref packages, which make use of the facilities of hyperref.

The package depends on the author’s kvoptions, ltxcmds and refcount packages.

https://ctan.org/pkg/hyperref?lang=en

\usepackage[utf8]{inputenc}

inputenc – Accept different input encodings
The pack­age trans­lates var­i­ous stan­dard and other in­put en­cod­ings into a ‘LATEX in­ter­nal lan­guage’. The in­ter­nal lan­guage is ex­pressed en­tirely in TEX's base en­cod­ing (stan­dard ASCII print­able char­ac­ters, car­riage con­trol to­kens and TEX con­trol se­quences, the lat­ter mostly de­fined by LATEX).

https://ctan.org/pkg/inputenc?lang=en


\usepackage[english]{babel}

babel – Multilingual support for Plain TEX or LATEX
This pack­age man­ages cul­tur­ally-de­ter­mined ty­po­graph­i­cal (and other) rules for a wide range of lan­guages. A doc­u­ment may se­lect a sin­gle lan­guage to be sup­ported, or it may se­lect sev­eral, in which case the doc­u­ment may switch from one lan­guage to an­other in a va­ri­ety of ways.

Ba­bel uses con­tributed con­fig­u­ra­tion files that pro­vide the de­tail of what has to be done for each lan­guage. In­cluded is also a set of ini files for about 200 lan­guages.

Many lan­guage styles work with pdfLATEX, as well as with XELATEX and LuaLATEX, out of the box. A few even work with plain for­mats.

https://ctan.org/pkg/babel

\usepackage{amsthm}

amsthm – Typesetting theorems (AMS style)
The pack­age fa­cil­i­tates the kind of the­o­rem setup typ­i­cally needed in Amer­i­can Math­e­mat­i­cal So­ci­ety pub­li­ca­tions. The pack­age of­fers the the­o­rem setup of the AMS doc­u­ment classes (am­sart, ams­book, etc.) en­cap­su­lated in LATEX pack­age form so that it can be used with other doc­u­ment classes.

Am­sthm is part of the (re­quired) AMS-LATEX dis­tri­bu­tion, so should be present in any LATEX dis­tri­bu­tion.

https://ctan.org/pkg/amsthm

\usepackage{amsmath}

The prin­ci­pal pack­age in the AMS-LATEX dis­tri­bu­tion. It adapts for use in LATEX most of the math­e­mat­i­cal fea­tures found in AMS-TEX; it is highly rec­om­mended as an ad­junct to se­ri­ous math­e­mat­i­cal type­set­ting in LATEX.

When ams­math is loaded, AMS-LATEX pack­ages ams­bsy (for bold sym­bols), am­sopn (for op­er­a­tor names) and am­s­text (for text em­bed­ded in math­e­mat­ics) are also loaded.

ams­math is part of the LATEX re­quired dis­tri­bu­tion; how­ever, sev­eral con­tributed pack­ages add still fur­ther to its ap­peal; ex­am­ples are em­pheq, which pro­vides func­tions for dec­o­rat­ing and high­light­ing math­e­mat­ics, and nthe­o­rem, for spec­i­fy­ing the­o­rem (and sim­i­lar) def­i­ni­tions.

Not sure of the relation:

latex-amsmath – AMS mathematical facilities for LATEX
The pack­age pro­vides the prin­ci­pal pack­ages in the AMS-LATEX dis­tri­bu­tion. It adapts for use in LATEX most of the math­e­mat­i­cal fea­tures found in AMS-TEX; it is highly rec­om­mended as an ad­junct to se­ri­ous math­e­mat­i­cal type­set­ting in LATEX.

When ams­math is loaded, AMS-LATEX pack­ages ams­bsy (for bold sym­bols), am­sopn (for op­er­a­tor names) and am­s­text (for text em­bed­ded in math­e­mat­ics) are also loaded.

ams­math is part of the LATEX re­quired dis­tri­bu­tion; how­ever, sev­eral con­tributed pack­ages add still fur­ther to its ap­peal; ex­am­ples are em­pheq, which pro­vides func­tions for dec­o­rat­ing and high­light­ing math­e­mat­ics, and nthe­o­rem, for spec­i­fy­ing the­o­rem (and sim­i­lar) def­i­ni­tions

https://ctan.org/pkg/latex-amsmath

\usepackage{graphicx}

graphicx – Enhanced support for graphics
The pack­age builds upon the graph­ics pack­age, pro­vid­ing a key-value in­ter­face for op­tional ar­gu­ments to the \in­clude­graph­ics com­mand. This in­ter­face pro­vides fa­cil­i­ties that go far be­yond what the graph­ics pack­age of­fers on its own.

For ex­tended doc­u­men­ta­tion, see ep­s­la­tex.

The pack­age is part of the la­tex-graph­ics bun­dle, which is one of the col­lec­tions in the LATEX ‘re­quired’ set of pack­ages.

https://ctan.org/pkg/graphicx


https://ctan.org/tex-archive/macros/latex/contrib/booktabs/

The package enhances the quality of tables in LATEX, providing extra commands as well as behind-the-scenes optimisation. Guidelines are given as to what constitutes a good table in this context. From version 1.61, the package offers longtable compatibility.

[Note: Does not support header and cell merging?]

Online table editor does support (and provides cut and paste from spreadsheets etc)

https://www.tablesgenerator.com/help/latex-tables/borders-editing

---


Also will need tensors.

Several packages listed in search:

https://ctan.org/search?phrase=tensor

The search found 6 of 6 hits in 19ms.

Pack­age ten­sor
Type­set ten­sors
Last mod­i­fied in Cat­a­logue: 2018-01-03 12:23

Pack­age fn­spe
Macros for sup­port­ing mainly stu­dents of FNSPE CTU in Prague
Last mod­i­fied in Cat­a­logue: 2018-01-03 12:20

Pack­age hht­en­sor
Print vec­tors, ma­tri­ces, and ten­sors
Last mod­i­fied in Cat­a­logue: 2018-01-03 12:22

Pack­age mat­tens
Ma­tri­ces/ten­sor type­set­ting
Last mod­i­fied in Cat­a­logue: 2018-01-03 12:22

Pack­age iso­math
Math­e­mat­ics style for sci­ence and tech­nol­ogy
Last mod­i­fied in Cat­a­logue: 2018-01-06 12:34

Pack­age tensind
Type­set ten­sors
Last mod­i­fied in Cat­a­logue: 2019-07-06 06:34

Note: None of the above have built in cwl files for TeXstudio. Review autogenerated cwl.

## File transfers

Initially just via Github. Later automatic rsync across Lan and Wan via dedicated server/backup and archives

## Backups

Separate folder for only the actual TeX including Bibliography files that I type.

Initially just load these to Github as both backup and file transfer. Use integration of Atom with Github desktop to simply keep in sync.

Use issue tracker to notify of updates via email subscription.

Later regular USB of just  that folder.

See separate document for comprehensive back up plan.

## Pandoc

After initial familiarization with Texmaker and Atom etc start using Markdown for faster and simpler drafting that is automatically formatted by Gitub and Gitlab and can be easily convered by pandoc and pandocomatic.

Produce a pandocomatic configuration that does exactly what the initial template does and then add to it.

## Markdown

Github Flavoured Markdown (GFM) provides all the facilities needed in initial template more simply.

### Headings
Three levels: Section, Subsection and Subsubsection. Can also do more and variant using underlines.

### Paragraphs
Juse use blank lines. Automatic indentation. Same for both.

### Italics

__italics__ instead of {\em italics}

### Left and right quotes

Converted automatically for "quoted phrase".

Can add lots more including LaTeX for maths etc.

Perhaps also start using LwDITA.

## Bibliography

Initially just a master Bibliography file for all Bibtex references with one paragraph explanations/descriptions.

Simply cut and paste from it to individual articles.

See separate file for later systems using Zotero and integrated with Library Genesis, Sci-Hub, Library of Congress, Worldcat, crossref, Web of Science,  doi and ISBN, ISSN, ASIN etc and with Calibre and Pandoc and other software.

Also for quickly cataloging and sorting actual books and periodicals and tracking locations.
