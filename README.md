# Sage Intacct Web Services Schemas


## ⚠️ Deprecation Notice ⚠️  

As of **Sage Intacct 2025 Release 1** (February 2025), the **REST API** are **Generally Available (GA)**.  
With this, we are **no longer actively developing enhancements** for the DTD and XSD schemas.  

Developers can continue using these schemas, but any future changes, maintenance, and feature development will be **self-managed**.  
For new integrations, we strongly recommend using the [REST API](https://developer.sage.com/intacct/docs/).  

For any questions, refer to our [developer support](https://developer.sage.com/intacct/docs/developer-portal/rest-api-faq/).

---



As XML requests are passed through the Sage Intacct Web Services Gateway, they are parsed and validated against a DTD or XSD.  Depending on the version of the request,

* 2.1 is validated against the DTD files inside the v2.1 folder.
* 3.0 is validated against the XSD file inside the v3.0 folder.

Your XML requests must be constructed carefully in order to avoid an error response from the Gateway.

Learning to read the DTD and XSD files will help you write valid XML more consistently.

## Issues

**This repository is read-only.** If you have any issues, please open a case with Sage Intacct Customer Support at https://community.intacct.com

## Resources

* [Sage Intacct][intacct] - Sage Intacct's home page
* [License][schema-license] - Apache 2.0 license

## Updates

These files are updated periodically as Sage Intacct does major and off cycle releases.

[intacct]: http://www.intacct.com
[schema-license]: http://www.apache.org/licenses/LICENSE-2.0
