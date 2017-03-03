# javascript

The following command line destructively chops the transparent layer of the pdf file:
"C:\Program Files\gs\gs9.20\bin\gswin64c.exe" -q -dPDF -dNOPAUSE -sProcessColorModel=DeviceRGB -dUseCropBox -r300x300 -sDEVICE=pdfwrite -sPDFACompatibilityPolicy=1 -sOutputFile=A1.0-ASEC-20030601-OC-FLA-FLA.pdf A1.0-ASEC-20030601-OS-FLA-FLA.pdf -c quit

While this one tests to show that the pdf file when coverted to jpg or tiff has a transparent layer.  (if it does, it will convert it to white-space.
"C:\Program Files\gs\gs9.20\bin\gswin64c.exe" -q -dNOPAUSE -r300x300 -sDEVICE=tiff24nc -sOutputFile=output.tif A1.0-ASEC-20030601-OS-FLA-FLA.pdf -c quit

