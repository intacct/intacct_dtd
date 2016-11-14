# Intacct Web Services Schemas

As XML requests are passed through the Intacct Web Services Gateway, they are parsed and validated against a DTD or XSD.  Depending on the version of the request,

* 2.1 is validated against the DTD files inside the v2.1 folder.
* 3.0 is validated against the XSD file inside the v3.0 folder.

Your XML requests must be constructed carefully in order to avoid an error response from the Gateway.

Learning to read the Intacct DTD and XSD files will help you write valid XML more consistently.

## Resources

* [Intacct][intacct] - Intacct's home page
* [License][schema-license] - Apache 2.0 license

## Updates

These files are updated periodically as Intacct does major and off cycle releases.

[intacct]: http://www.intacct.com
[schema-license]: http://www.apache.org/licenses/LICENSE-2.0