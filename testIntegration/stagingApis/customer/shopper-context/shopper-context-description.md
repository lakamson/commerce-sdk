# API Overview

_**Note:** This feature is a Beta Service. You may opt-in to try this service at your sole discretion. Any use of this service is subject to the [Customer Agreements and User Terms for Products and Services](https://www.salesforce.com/company/legal/agreements/)._

With the Shopper Context API, you can set any context information as a key/value pair and use it to retrieve personalized promotions, payment methods, and shipping methods. The context information that is set is evaluated against the customer group definitions to determine a customer group (shopper segment) and then used to activate the experiences that are associated with a particular segment, such as promotions.

You can also get personalized API responses triggered by shopper context from the [Open Commerce API](https://documentation.b2c.commercecloud.salesforce.com/DOC1/topic/com.demandware.dochelp/OCAPI/current/usage/OpenCommerceAPI.html) (OCAPI). Support for both the B2C Commerce API and OCAPI allows shopper context to be used in hybrid deployments.

**Important:** For detailed usage information, see the [Shopper Context guides](https://developer.salesforce.com/docs/commerce/commerce-api/guide/shopper-context-api.html).

To use the Shopper Context API, you must:

- Get a JSON Web Token (JWT) for the Shopper Login and API Access Service (SLAS).
- Add `sfcc.shopper-context.rw` to the scopes configuration for the SLAS API client.

For more information, see [Authorization for Shopper APIs](https://developer.salesforce.com/docs/commerce/commerce-api/guide/authorization-for-shopper-apis.html) in the Get Started guides.

**Warning**: As with all APIs, never store access tokens in the browser because this creates a security vulnerability.
