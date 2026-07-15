# Telegram Order Notification Workflow


## Overview

Automatically notify customers after a digital product purchase.

This workflow connects:

- Payhip
- Make Automation
- Telegram Bot
- Notion Database


## Workflow


Customer Purchase

↓

Payhip Payment Received

↓

Webhook Trigger

↓

Make Automation

↓

Telegram Customer Notification

+

Notion Order Record


## Architecture

Payhip
|
|
Webhook
|
|
Make Automation
|
|-------- Telegram Bot
|
|-------- Notion Database



## Tools Used


| Tool | Purpose |
|---|---|
| Payhip | Payment processing |
| Make | Workflow automation |
| Telegram Bot | Customer notification |
| Notion | Order database |



## Example Use Case


A customer purchases a digital product.

The system automatically:

1. Receives payment confirmation
2. Triggers automation workflow
3. Sends Telegram notification
4. Records order information in Notion



## Benefits


- No manual delivery
- Faster customer response
- Centralized order tracking
- Lightweight automation stack



## Setup


1. Create Payhip product
2. Configure webhook trigger
3. Import Make scenario
4. Connect Telegram Bot
5. Connect Notion database



## Status


Example workflow for Hermes automation ecosystem.

