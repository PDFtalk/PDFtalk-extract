# PDFtalk-extract
Extract contents and data from PDF pages

This is an extension for the PDFtalk library and depends on it.

This is experimental and not ready for production.

The aim is to extract the basic text and graphic elements and reconstruct higher level structures from them.
At the lowest level, all graphical "atoms" are constructed with their exact position.

From here, we may identify layout from the texts: titles, paragraphs, columns and tables.
