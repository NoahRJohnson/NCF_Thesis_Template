# NCF_Thesis_Template
I recommend you download and use Tex-Studio to compile your document. Open main.tex in that, or some editor, and read it and the comments. That is the start point for the compilation.

In order to cite your references, make sure Biber is installed. Open exampleBib.bib, and read it to understand the syntax. Create your own references there. Then use \cite{nameOfRef} in .tex files, where nameOfRef is the name of one of the entries in your .bib file. Then compile, run "biber main.bcf" from the command line, and recompile.
