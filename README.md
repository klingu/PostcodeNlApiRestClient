Postcode.nl API REST Client
=============

A ASP.NET 4.5.1+ class, which offers methods to directly talk with the [Postcode.nl API](https://api.postcode.nl/documentation) through the REST endpoint offered.
You will need to create an account with the [Postcode.nl API](https://api.postcode.nl) service.

Implements both the [Address service](https://api.postcode.nl/documentation/address-api-description) and the [Signal service](https://api.postcode.nl/documentation/signal-api-description).

License
=============

The code is available under the open source Simplified BSD license. (see LICENSE.txt)

Installation
=============

The best way to install is by using [PHP Composer](https://getcomposer.org/), get package [`postcode-nl/api-restclient`](https://packagist.org/packages/postcode-nl/api-restclient) and stay up to date easily.

Or download the source from our GitHub page: https://github.com/postcode-nl/PostcodeNl_Api_RestClient

Usage Address API
=============

Include the class in your ASP.Net project, instantiate the ASP.Net class with your authentication details and call the 'lookupAddress' method.
You can handle errors by catching the defined Exception classes.

* See our [Address API description](https://api.postcode.nl/documentation/address-api-description) for more information
* See our [Address API method documentation](https://api.postcode.nl/documentation/rest-json-endpoint#address-api) for the possible fields

Usage Signal API
=============

Include the class in your ASP.Net project, instantiate the ASP.Net class with your authentication details and call the 'doSignalCheck' method.
You can handle errors by catching the defined Exception classes.

* See our [Signal API description](https://api.postcode.nl/documentation/signal-api-description) for more information
* See our [Signal API check method documentation](https://api.postcode.nl/documentation/rest-json-endpoint#signal-api) for the possible fields to pass.
* See our [basic example](https://api.postcode.nl/documentation/signal-api-example) for a practical example
