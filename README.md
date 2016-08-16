# Eldoc

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)

Eldoc is a **document template** for producing clean, elegant reports. Built with the [LaTeX] (http://www.latex-project.org) typesetting system, it's highly-configurable and doesn't require proprietary text-editing software.

![Eldoc Screenshot](http://i.imgur.com/A3WtMHv.png)

## Why Use It?

The high-quality presentation of reports is paramount, regardless of what content you're providing. LaTeX provides a powerful system in which to create high-quality reports,
but getting started with it can be slow and confusing. This template solves that problem by providing a well-commented framework which you can expand upon, fill with your own content, 
and use to generate a neatly-formatted, beautiful report.

## Pre-requisites

1. An installed TeX distribution, e.g. [MiKTeX] (http://www.miktex.org) or [TeX Live] (http://www.tug.org/texlive)
1. A LaTeX editor, such as [Texmaker] (http://www.xm1math.net/texmaker)
1. Note that combined intallation packages exist, e.g. [proTeXt] (http://www.tug.org/protext), which combine the TeX distribution & editor (the editor is TeXStudio in this in the case of proTeXt)

## User Guide

1. Ensure that the pre-requisites are installed.
1. Run the .tex file using your LaTeX editor. This will allow you to make edits & to write your content.
1. When including images, it's best to use vector images since they scale without becoming pixelated. Create your image in LibreOffice Impress or Microsoft Powerpoint, export it to PDF, and importantly (!) crop the PDF to remove surrounding whitespace. Save the cropped PDF in your Images folder and refer to it from your LaTeX source code. If you're using Powerpoint, make sure to right-click your slide, select Format Background and tick 'Hide background graphics' to prevent your image backgrounds having a grey-fill.
1. Ensure that library file is within the 'BibTeX_Libraries' folder, & that this folder resides in the same directory as the .tex file you're compiling. Reference management software such as [Mendeley] (http://www.mendeley.com), can automatically generate this .bib file for you. Make sure not include any whitepace in the name of this .bib file, or else your references won't be defined in your LaTeX document.
1. To compile for the first time, run/compile your LaTeX source code by running PDFLaTeX ('PDFLaTeX' dropdown adjacent to Texmaker's Run command) in order to create the .aux file. Other files will also be created in the same folder as your .tex file.
1. Now create the .bbl (reference) file by running BibTeX ('BibTeX' dropdown adjacent to Texmaker's Run command). The previous step - the creation of the .aux file - is a pre-requisite to this step.
1. Compile your LaTeX source code by running PDFLaTeX again. Display your PDF document by opening the file directly from the same directory as your .tex file, or by using the "View PDF" button in Texmaker to view it in an adjacent window to your source code.
1. If at first your PDF doesn't update.. build again.

## Author

Ian Campbell | [LinkedIn] (https://uk.linkedin.com/in/icampbell1) | [Twitter] (http://www.twitter.com/@Ian_Campbell1)

## Licensing

Eldoc is free software, licensed under the short, permissive [MIT Licence] (http://www.choosealicense.com/licenses/mit). Under this licence, you're free to do whatever you like with the software as long as you acknowledge me as the author, and don't hold me liable if it all goes horribly wrong.

## Feedback & Improvements

Code pull requests and/or e-mail are very welcome!

## Related Resources

* [CTAN] (http://www.ctan.org) - for LaTeX package descriptions
* [MiKTeX] (http://www.miktex.org) - Windows TeX distribution
* [proTeXt] (http://www.tug.org/protext) - a MiKTeX-based TeX distribution for Windows, including an editor
* [Texmaker] (http://www.xm1math.net/texmaker) - a TeX editor
* [TeXstudio] (http://www.texstudio.org) - an alternative TeX editor
* [LibreOffice Impress] (http://www.libreoffice.org/discover/impress) - for creating vector images in PDF format
* [MS Powerpoint] (https://products.office.com/en-gb/powerpoint) - for creating vector images in PDF format

