

This n8n workflow allows users to create a disposable, masked email address using the Fastmail API, triggered by a webhook.

Example: A user or application can send a POST request to a specific webhook with a JSON payload containing the desired state and description for the masked email. The workflow then creates the masked email address and responds with the generated email and its description, which can be used for various purposes, such as privacy-conscious communication or testing.

## What You Can Do
- Webhook-triggered creation of masked email addresses
- Customizable state and description for the masked email
- Secure integration with the Fastmail API using HTTP header authentication
- Flexible output format, with the generated email address and description returned in the webhook response

