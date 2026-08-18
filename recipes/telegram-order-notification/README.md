# Telegram Order Notification

Automatically receive a Telegram notification whenever a new digital product order is completed.

This recipe is designed for creators and digital product businesses that want to monitor new orders without manually checking their payment platform.

## Use Case

This workflow can be used to:

- Receive new order notifications
- Monitor customer activity
- Track completed payments
- Get real-time order alerts
- Reduce manual checking

## Tools

- Payhip
- Make
- Telegram

## Workflow

```text
Payhip
   ↓
Make
   ↓
Telegram

When a new order is completed:

Payhip triggers the workflow.
Make receives the order event.
Make processes the order information.
Telegram sends a notification.
Example Notification

A notification can include information such as:

Customer name
Customer email
Product name
Order amount
Order date
Order status

Example:🛒 New Order

Product: Digital Product
Customer: customer@example.com
Amount: $19
Status: Paid

A new order has been received.

Setup
1. Prepare Payhip

Create a Payhip product and make sure your store is ready to receive orders.

You will need access to your Payhip account and order information.

2. Create a Make Scenario

Create a new scenario in Make.

Add the required Payhip or webhook trigger for your order workflow.

3. Connect Telegram

Add a Telegram Bot module to the Make scenario.

Connect your Telegram bot and select the chat where order notifications should be sent.

4. Map Order Data

Map the relevant order information from Payhip into the Telegram message.

For example:

. Product name
. Customer email
. Order amount
. Order status
. Order date

5. Test the Workflow

Create a test order and verify that:

. Make receives the order event
. The order data is mapped correctly
. Telegram receives the notification
. Automation Logic

New Payhip Order
        ↓
Receive Order Data
        ↓
Process Order in Make
        ↓
Format Notification
        ↓
Send Telegram Message

Related Resources
. Recipe Library
. Hermes Automation Examples

Related Workflow

View the Telegram Order Notification workflow

What You Can Customize

You can adapt this recipe to:

. Add different notification formats
. Send notifications to multiple Telegram chats
. Add customer segmentation
. Store order information in Notion
. Trigger additional automation steps
. Connect other business tools

Notes

This recipe is an example workflow and should be adapted to your own Payhip, Make and Telegram configuration.

Do not expose API keys, bot tokens, webhook secrets or customer information in your public repository.

## Related resources

- [Telegram Order Notification Workflow](../../telegram-order-notification/)
