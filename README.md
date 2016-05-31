Elegant LaTeX document template for reporting

Contact
-----------
- Author = Ian Campbell
- GitHub = www.github.com/icampbell1
- Twitter = www.twitter.com/@Ian_Campbell1

Feedback & improvements
-----------
Code pull requests and/or e-mail are very welcome

Licecning
-----------
Please refer to Licence.txt

Version Guide:
-----------
v1.0
Baseline release

What is it?
-----------
Getting started with LaTeX can be confusing, and it's often much easier to begin with a code template than from
scratch. This .tex file is one such template, orginally used for a PhD plan, now generalised & made available online. While 
it doesn't inlcude every common LaTeX command, it aims to provide a well-commented framework which you can expand 
to create your own neatly-formatted, highly-presentable document.

If you're already proficient with a word-processing program, you may wonder why it might be beneficial to learn
LaTeX. Here are some reasons:

1) It's free! Not everyone can afford a licence for proprietary word-processing software. By creating your document
in LaTeX, you reduce a barrier to others using, editing and evolving your work.

2) It gives you complete control over your document's format.

3) You might prefer the command-based environment.

4) For very large documents, it may be more responsive than other word-procesing programs. I haven't yet tested 
this, so let me know :)

Happy writing!

Documentation
-----------
Pre-requisites:
- An installed TeX distribution, e.g. MiKTeX for Windows (www.miktex.org) or 
  TeX Live for Linux (www.tug.org/texlive)
- A LaTeX editor, such as Texmaker (www.xm1math.net/texmaker)
- Note that combined intallation packages exist, e.g. proTeXt, which combine
  the TeX distribution & editor (the editor is TeXStudio in this in the case of proTeXt) (www.tug.org/protext)

User Guide:

1) Ensure the pre-requisites are installed.

2) Run the .tex file using your LaTeX editor. This will allow you to make edits & to write your content.

3) When including images, it's best to use vector images since they scale without becoming pixelated. Create your image in LibreOffice Impress or Microsoft Powerpoint, export it to PDF, and importantly (!) crop the PDF to remove surrounding whitespace. Save the cropped PDF in your Images folder and refer to it from your LaTeX source code. If you're using Powerpoint, make sure to right-click your slide, select Format Background and tick 'Hide background graphics' to prevent your image backgrounds having a grey-fill. As of May 2016, www.sejda.com/crop-pdf & www.pdfescape.com both offer an online PDF cropping service.

4) Ensure that library file is within the 'BibTeX_Libraries' folder, & that this folder resides in the same directory as the .tex file you're compiling. Reference management software such as Mendeley, www.mendeley.com, can automatically generate this .bib file for you. Make sure not include any whitepace in the name of this .bib file, or else your references won't be defined in your LaTeX document.

5) To compile for the first time, run/compile your LaTeX source code by running PDFLaTeX ('PDFLaTeX' dropdown adjacent to Texmaker's Run command) in order to create the .aux file. Other files will also be created in the same folder as your .tex file.

6) Now create the .bbl (reference) file by running BibTeX ('BibTeX' dropdown adjacent to Texmaker's Run command). The previous step - the creation of the .aux file - is a pre-requisite to this step.

7) Compile your LaTeX source code by running PDFLaTeX again. Display your PDF document by opening the file directly from the same directory as your .tex file, or by using the "View PDF" button in Texmaker to view it in an adjacent window to your source code.

8) If at first your PDF doesn't update.. build again.

Related Resources
-----------
- www.ctan.org for package descriptions
- www.miktex.org - Windows TeX distribution
- www.tug.org/protext - a MiKTeX-based TeX distribution for Windows, including an editor
- www.xm1math.net/texmaker - a TeX editor
- www.texstudio.org - an alternative TeX editor
- www.libreoffice.org/discover/impress - Useful free tool for creating vector images in PDF format
- https://products.office.com/en-gb/powerpoint - Useful tool for creating vector images in PDF format

