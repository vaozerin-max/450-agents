

This workflow monitors a RabbitMQ queue, checks if the value of the "temp" parameter exceeds 50, and sends an alert via Vonage if the condition is met.

Example: This workflow could be used to monitor a temperature sensor that sends data to a RabbitMQ queue. If the temperature exceeds a certain threshold (in this case, 50 degrees), the workflow will send an alert to a designated phone number, allowing the user to take immediate action.

## What You Can Do
- Triggers on new messages in a RabbitMQ queue
- Checks the value of a specific parameter ("temp") against a predefined threshold
- Sends an alert via Vonage if the condition is met
- Provides a "no-op" node for cases where the condition is not met

