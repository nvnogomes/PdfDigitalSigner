# PdfDigitalSigner
A JavaFX application can sign, extract revisions and preview the pdf document.

This application allows the signature of pdf document in the client machine, of a document that exists in a server machine.
All the operations made to the pdf document are made with the iTextPdf library.
The application is composed by two components. A Java program that manipulates the PDF document, and a ASPX web site that stores the signed or extracted revision in the server machine.


Java security:
Java requires that all jar packages are signed. This can be done with a CA generated certificate or a self-signed certificate.
If you opt for the former, you must add the IP of the server machine that holds the JARs in the Exception list in the Java Control Panel.

<to be completed...>
