# Information
(Almost complete) Bachelor/Master thesis template for the University of Gävle
Used in the programmes for computer engineering and computer science.

Layout design: ATM @ University of Gävle


### URLs: 
*Formatting instructions (Swedish):* https://www.hig.se/download/18.1324506a15dbb2aec243f6b8/1503327750955/formateringsinstruktion_examensarbete_-_ATM.pdf

*Template (Swedish):* https://www.hig.se/download/18.36f068b215bca725a754cb7/1556552581046/mall_f%C3%B6r_examensarbete_-_ATM.docx

*Instructions on writing (Swedish):* https://www.hig.se/download/18.6c77c68166435adf0b1a3d9/1540307983766/skrivhandbok_examensarbete_-_ATM.pdf

*Miscellaneous information:* https://www.hig.se/Ext/Sv/Organisation/Akademier/Akademin-for-teknik-och-miljo/Studentinformation/Examensarbete/Handledningar-och-mallar.html

## Purpose
No LaTeX template exists (AFAIK), and the university utilizes Word as its primary editor.
WYSIWYGs are not for everyone and can be tedious to work on when you do many iterations.

## Disclaimer
It is difficult to adhere to the formatting instructions given by the university due to the peculiarities encapsulated within Word. 
E.g. "hanging" after a header. Another challenge is the selection of the main font, Perpetua, which is not available (for free, to the best of my knowledge) in LaTeX.
The fourth (subsubsection, 1.1.1.1) level of heading does not work at the moment and generates an error. According to the instructions you are to refrain to use this level in the thesis report.

Made with Visual Studio Code, not tested online (E.g. Overleaf).

## Tips & Tricks
When using the template with Visual Studio Code. Always clean auxiliary files when building the document; this will help with problems related to the bibliography.


## Document specific commands
HiGQuote (\begin{HiGquote}) adheres to the rules stipulated in the formatting instructions.

The document is not in class "article" but in "book" so the levels for headings are (in order from biggest to smallest); chapter, section, subsection, subsubsection.


*Keywords:* DVA010C DVG800 HiG mall_för_examensarbete_-_ATM.docx skrivhandbok_examensarbete_-_ATM.docx HIG Dataingenjörsprogrammet Datavetenskapliga TGDVK TGDAY Examensarbete dataingenjör datavetenskap