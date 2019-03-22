# CFEE Eirini Storefront


This repo consists of a [backend COBOL app](https://github.com/IBM-Cloud/cfee-eirini-storefront/tree/master/backend) and a [frontend Node App](https://github.com/IBM-Cloud/cfee-eirini-storefront/tree/master/frontend). The focus here is to understand how these two apps can be deployed and managed with one Cloud Foundry Enterprise Environment instance.

A frontend Node.js shopping cart app is talking to the backend Cobol app to fetch the shopping cart products.

## Architecture

![Architecture](./MD-images/Architecture.png)

Steps involved:

1. Deploy the [backend COBOL app](https://github.com/IBM-Cloud/cfee-eirini-storefront/tree/master/backend).
1. Deploy the [frontend Node.js app](https://github.com/IBM-Cloud/cfee-eirini-storefront/tree/master/frontend).

# Issues

If you have any question or doubt, please [create an issue](https://github.com/IBM-Cloud/cfee-eirini-storefront/issues).


# License

Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).