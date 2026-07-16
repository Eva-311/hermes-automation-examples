# Telegram Order Notification Workflow


## Overview

Automatically notify customers after a digital product purchase.

This workflow demonstrates how Hermes connects payment, automation, messaging, and database systems into a lightweight digital business workflow.

Built with:

- Payhip
- Make Automation
- Telegram Bot
- Notion Database


---

## Workflow


Customer purchases a digital product

↓

Payhip payment received

↓

Webhook trigger

↓

Make Automation workflow runs

↓

Customer receives Telegram notification

+

Order information is stored in Notion



---

## Architecture


## Architecture

![Hermes Automation Architecture](../diagrams/hermes-architecture.png)

## Example Scenario

A customer purchases a digital product.

The automation system:

1. Receives payment confirmation from Payhip
2. Triggers the Make workflow
3. Sends a Telegram notification
4. Records customer information in Notion

The entire delivery process runs automatically without manual operation.

## Setup

### Requirements

- Payhip account
- Make account
- Telegram Bot
- Notion database


### Configuration

1. Create a Payhip product
2. Configure webhook trigger
3. Import Make automation scenario
4. Connect Telegram Bot
5. Connect Notion database
