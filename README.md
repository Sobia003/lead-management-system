# Lead Management System

## Overview
An automated lead management workflow built with n8n and HubSpot CRM. It captures incoming leads, validates their information, creates CRM contacts and deals, assigns sales representatives, and sends automated email notifications.

## Features
- Lead capture through a webhook
- Automatic lead data validation
- HubSpot contact creation
- Salesperson assignment using an n8n Data Table
- Automatic HubSpot deal creation
- Email notifications to sales representatives
- Automated acknowledgement emails to leads

## Workflow
1. A lead submits their information through a webhook.
2. The workflow validates the required fields.
3. A contact is created in HubSpot.
4. A salesperson is assigned using the Data Table.
5. A deal is created in HubSpot.
6. Email notifications are sent to the salesperson and lead.

## Technologies
- n8n
- HubSpot CRM
- JavaScript
- Webhooks
- n8n Data Tables
- SMTP / Email Integration

## Setup Notes
After importing the workflow, configure your own HubSpot and SMTP credentials. Select or configure your own n8n Data Table and update the HubSpot owner ID and email placeholders.
