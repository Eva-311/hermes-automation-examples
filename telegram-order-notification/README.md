Telegram Order Notification Workflow

An automated customer delivery workflow for digital product businesses using Payhip, Make, Telegram, and Notion.


## Overview

This automation workflow helps digital creators receive instant Telegram notifications after a customer purchases a product.

### Problem

Creators often need to manually check payment platforms for new orders.

This workflow removes that manual step by connecting:

Payhip → Make → Telegram

When a payment is completed, the system automatically sends an order notification.

## Tools Used

| Tool | Purpose |
|---|---|
| Payhip | Payment processing |
| Make | Workflow automation |
| Telegram Bot | Customer notification |
| Notion | Order management |
---

This workflow automatically processes order events without manual checking.

## Workflow

1. Customer purchases a digital product

2. Payhip confirms payment

3. Webhook receives order event

4. Make Automation processes workflow

5. Telegram sends customer notification

6. Order information is stored in Notion

## Architecture

![Hermes Automation Architecture](../diagrams/hermes-architecture.png)
The architecture connects payment, automation, communication, and database layers into one automated workflow.

## Example Scenario


A creator sells a digital product through Payhip.

When a customer completes payment:

1. Payhip sends a webhook event.
2. Make processes the order information.
3. Telegram Bot sends an instant notification.
4. The creator knows about the new order immediately.

The entire delivery process runs automatically without manual operation.

## Setup

Requirements

- Payhip account for digital product sales
- Make account for workflow automation
- Telegram Bot for customer messaging
- Notion database for order management

### Configuration

1. Create a Payhip product
2. Configure webhook trigger
3. Import Make automation scenario
4. Connect Telegram Bot
5. Connect Notion database


## Preview

Workflow example:

![Telegram Order Workflow](../../assets/images/telegram-order-notification.png)


## Status

Active example workflow for the Hermes automation ecosystem.

More automation templates and integrations will be added in future updates.

## Related Project

This workflow is part of Hermes Automation Examples.

The complete Digital Product OS includes:

- Automated product delivery
- Notion business dashboard
- Customer management
- Follow-up automation

Learn more:
Payhip link：https://payhip.com/EvasDigitalToolkit
