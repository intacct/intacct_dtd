Intacct DTD and XSD Files
=========================

As XML requests are passed through the Intacct Web Services Gateway, they are parsed and validated against a DTD or XSD:

* When a version 2.1 request is sent, it is validated against the DTD files inside the v2.1 folder.
* When a version 3.0 request is sent, it is validated against the XSD file inside the v3.0 folder.

Your XML requests must be constructed carefully in order to avoid an error response from the Gateway.

Learning to read the Intacct DTD and XSD files will help you write valid XML more consistently.

## Updates
These files are updated periodically as Intacct does major and off cycle releases.