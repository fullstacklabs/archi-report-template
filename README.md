# Generating clean PDFs from .archimate files with Archi

[Archi](https://www.archimatetool.com/) is an open source ArchiMate model editing tool.  By default it can export reports as PDFs, but they contain a styled background and a lot of extra metadata that can make then quite long for large models (300+ pages).  The template in this repository creates PDFs with plain white backgrounds and only includes the model diagrams, which are high resolution enough to zoom in to see detail in large models.  This is important as the HTML reports don't currently allow zooming to higher levels of detail.

To use this diagram (on a Mac):

- [install Archi](https://www.archimatetool.com/download/)
- In ````/Users/[your username]/Library/Application Support/Archi4/jasper-reports/```` make a new directory called ````CleanTemplate````
- Copy the contents of this repository into that directory
- Open your model in Archi
- Click File -> Report -> Jasper…
- Set location, filename and title to what you want, select “PDF”
- Click “Next”
- In the “Report Template” dropdown, select “CleanTemplate”
- Click “Finish”, report will be generated in the location you set previously

Once you've generated the PDF, Adobe offeres a sharing services which allows you to send it out to others for feedback and review:

[https://acrobat.adobe.com/us/en/acrobat/how-to/annotate-pdf-online.html](https://acrobat.adobe.com/us/en/acrobat/how-to/annotate-pdf-online.html)
