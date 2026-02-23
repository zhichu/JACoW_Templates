
## JACoW 3.00

2026-02

The `jacow` class is used for submissions to the proceedings of conferences on the »Joint Accelerator Conferences Website« (JACoW), an international collaboration that publishes the proceedings of accelerator conferences held around the world. 

See the JACoW website for more information <https://jacow.org/>

This package has been developed as a common »template« for papers destined for electronic production for Accelerator Conferences together with a »style guide« to show specific key features how to typeset units, isotopes and elements, and recommendations for good scientific writing.

## `jacow.cls`

* Authors (1996—2026)
  - John Jowett (CERN)
  - Michel Goossens (CERN)
  - Martin Comyn (TRIUMF)
  - John Poole (CERN)
  - Todd Satogata (BNL)
  - Ulrike Fischer (Troubleshooting TeX)
  - Marei Peischl (πTeX)
  - Zhichu Chen (SARI)
  - Volker RW Schaa (GSI)

* Version:    
  - 3.00 (maintenance release)
  
* Date:       
  - 19 February 2026
  
* Copyright:  
  - 1996-2026 by JACoW, Geneva, Switzerland

* Homepage:   
  - <https://www.jacow.org>

* github:   
  - <https://github.com/JACoW-org/JACoW_Templates>

* License:    
  - LPPL 1.3c
  
* Status:     
  - Maintained

* Maintainer: 
  - Volker RW Schaa & Zhichu Chen
  
## A BRIEF DESCRIPTION OF THE PACKAGE

The package consists of three parts. 
1) The **Class File** with BibLaTeX bibliography and cite style. 
2) A basic **Template** file of one typeset page. This page uses all the key features of the class. 
3) And there is an extended **Style Guide**. This guide covers all aspects of typesetting for conference proceedings, such as referencing figures, tables, and equations, formatting units, isotopes, elements, and compounds. In addition it gives an overview of all types of reference formatting, covering conference proceedings, journal article, publications in periodicals, online resources, books, reference manuals. Special emphasis is placed on DOIs. The guide also has recommendations for good scientific writing.

### Class File
This package consists of the following files
   - **`jacow.cls`**               
     JACoW class file
   - **`jacow.bbx`**               
     JACoW's biblatex bibliography style
   - **`jacow.cbx`**               
     JACoW's biblatex cite style

### Template     

a short example listing the key features of the JACoW class 
   - **`jacow_latex_template.tex`**		   
     template source and PDF to demonstrate the use of basic functionality 
   - **`jacow_latex_template.pdf`**  
     PDF of the template file `jacow_latex_template.tex`
   - **`jacow_latex_template_bib.tex`**  
     same as above but with BibLaTeX
   - **`jacow_latex_template_bib.pdf`**   
	 PDF of the template `jacow_latex_template_bib.tex` using BibLaTeX
   - **`jacow_latex_template_bib.bib`**    
     bib file for use with `jacow_latex_template_bib.tex`
   - **`jacow_pagesize.png`**	   
     schematic of the JACoW page size (used in `jacow_latex_template.tex` and `jacow_latex_style_guide.tex`)
   - **`jacow_picture1.png`**   
     example picture for graphics inclusion
   - **`jacow_picture2.png`**   
     example picture for graphics inclusion
    
## JACoW LaTeX Style Guide
This guide covers all aspects of typesetting for conference proceedings with recommendations for good scientific writing, and much more…

   - **`jacow_latex_style_guide.tex`**   
     - `JACoW LATEX STYLE GUIDE (v.2026-02-19)`
    JACoW Style Guide and Appendix B source files (Appendix B had been included in the source file to prevent active links of DOIs got lost)
   - **`jacow_latex_style_guide.pdf`**   
     - PDF of `jacow_latex_style_guide.tex` together with following two Appendices (A, C)
   - **`jacow_latex_appendix_a.tex`**
     - `Appendix A: FORMATTING OF AUTHORS AND AFFILIATIONS`
     showing the different ways of author and affiliation formatting
   - **`jacow_latex_appendix_a.pdf`**
     - PDF of `jacow_latex_appendix_a.tex`, this PDF is included in the Main Style Guide
   - **`jacow_latex_appendix_c.pdf`**
     - `Appendix C: JOURNAL ABBREVIATIONS`
       contains a list of often used journal abbreviation according to ISO 4. This file is part of the `JACoW Word Style Guide` and is included in the Main Style Guide. There is no companion `tex` file
   - **`jacow_groupphoto_tm2025.jpg`**
     - Group picture of the last JACoW Team Meeting in Nov. 2025 at CERN. It is included in `jacow_latex_style_guide.tex` 

## License
This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either
version 1.3c of this license or (at your option) any later
version. This version of this license is in
    <https://www.latex-project.org/lppl/lppl-1-3c.txt>
and the latest version of this license is in
    <https://www.latex-project.org/lppl.txt>
and version 1.3 or later is part of all distributions of
LaTeX version 2008-05-04 or later.
