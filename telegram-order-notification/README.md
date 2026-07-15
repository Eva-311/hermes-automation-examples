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


```text
Payhip
   |
   v
Webhook Trigger
   |
   v
Make Automation
   |
   +----------------+
   |                |
   v                v
Telegram Bot     Notion Database
(Customer        (Order Records)
Notification)

