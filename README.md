# Experience Cloud Checkout Flow

## Deploy
[![Deploy to Salesforce](https://app.jdeploy.cloud/images/flat.svg)](https://app.jdeploy.cloud/github/FinDockLabs/experience-cloud-checkout-flow/main)

This repository contains a Flow template to help you get started with building digital payment experiences using Experience Cloud and FinDock Payment Experiences. The Contact Flow is designed for commercial use cases such as invoices, subscriptions and recovering failed payments.

This template is meant to be customized and extended to fit specific use cases and requirements. For other options, see [Templates for FinDock Payment Experiences](https://github.com/FinDockLabs/experience-cloud-templates). 

*Key features*
- Collect new one-time payments
- Set up new recurring donations
- Pay existing one-time payments
- Update existing recurring payments

## Prerequisites
- FinDock is installed and configured.
- FinDock is the source of payments data ([FinDock Standalone](https://docs.findock.com/docs/source-connectors/findock-standalone)).
- At least one payment extension is installed and configured.
- Digital Experiences is enabled in the org.


## Installation
1. Press the buttons to deploy the repo to the org.
2. Follow [these instructions](https://help.salesforce.com/s/articleView?id=experience.rss_flow_guestuser.htm&type=5) to set up the guest user access for the flow. Do this for Checkout_Flow.
3. Go to the checkout Flow -> Payment Screen -> Payment Method Selection component
   - configure at least some payment methods
4. Configure the [payment intent](https://docs.findock.com/docs/july-26/payments/pay-button) (add at least a success and failure URLs and verify the mapping matches your use case).
6. Activate your flow.
7. Go to the Experience Cloud Administration -> Preferences -> enable "Allow guest users to access public APIs".
8. Add the flow to your Experience Cloud site.
