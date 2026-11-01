---
title: Subprocessors
updated_at: 2026-11-01
description: Current list of subprocessors and service providers that Bento, PostShiba, and Tatami use to help deliver the Services.
---

This page lists subprocessors and similar service providers that Backpack Internet Pty. Ltd. (trading as Bento Software) uses to help provide, secure, support, and improve its products: Bento, PostShiba, and Tatami.

If Bento processes customer personal information on your behalf, this page supplements our Data Processing Addendum, which you can review at [bentonow.com/gdpr/dpa](https://bentonow.com/gdpr/dpa) and sign in your account settings. The Data Processing Addendum currently covers Bento only.

We may update this page from time to time as our vendors and infrastructure change. Where required by contract or applicable law, we will provide additional notice before making material changes.

## How to read this page

- `Service provider` means the vendor or subprocessor.
- `Products` means which of our products use the vendor.
- `Purpose` means the general service the vendor helps us perform.
- `Customer data involved` means the main categories of customer or end-user data the vendor may process for that purpose.
- `Region` means the primary processing or hosting region we currently expect for that service. Actual processing locations may vary.

## Infrastructure and hosting

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| Heroku (Salesforce) | Bento, Tatami | Application hosting | Account data, contact data, event data, application records, logs | United States |
| Northflank | PostShiba | Application and mail server hosting, running on Google Cloud | Account data, message content, recipient email addresses, message metadata, delivery events, logs | United States |
| PlanetScale | Bento, PostShiba, Tatami | Managed database | Account data, contact data, event data, message metadata, application records | United States |
| Amazon Web Services (AWS) | Bento, PostShiba | Cloud infrastructure, storage, and DNS | Account data, contact data, event data, message metadata, application logs | United States |
| Elastic (Elastic Cloud) | Bento, Tatami | Search and analytics | Contact data, event data, delivery events, account identifiers | United States |
| DragonflyDB | Bento, Tatami | Redis-compatible data store for background jobs, queues, caching, rate limiting, and firewall rules | Any data the product processes while it passes through background jobs, including contact data, event data, message content, and session data | Varies |
| Redis Ltd. (Redis Cloud) | Bento | Caching | Account identifiers, session data, cached application data | United States |
| MemCachier | Bento, Tatami | Caching | Account identifiers, session data, cached application data | United States |
| Cloudflare | Bento, Tatami | CDN, DNS, edge security, and the Tatami MCP server | IP address, request metadata, cookies, security logs | Global |
| Vercel | Bento | Website hosting | Request metadata, contact details submitted through our website | United States |
| Cloudinary | Bento | Image hosting for marketing and email assets | Images and files you upload | United States |

## Email delivery

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| SendGrid (Twilio) | Bento | Email delivery | Recipient email addresses, message content, message metadata, delivery events | United States |
| Mailgun (Sinch) | Bento | Email delivery | Recipient email addresses, message content, message metadata, delivery events | United States |
| Hetzner | Bento, PostShiba | Self-hosted mail servers and sending proxies | Recipient email addresses, message headers, routing metadata, delivery logs | European Union |
| UpCloud | PostShiba | Sending proxies | Recipient email addresses, message headers, routing metadata, delivery logs | European Union |

## Product features

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| OpenAI | Bento, PostShiba, Tatami | AI features | Prompts, generated content, account identifiers, usage metadata | United States |
| Stripe | Bento, PostShiba, Tatami | Billing and payments | Billing contact details, transaction details, subscription data | United States |

## Security and abuse prevention

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| Spamhaus | Bento, PostShiba, Tatami | Link, domain, and IP reputation checks | Links and domains found in messages, sending IP addresses | Varies |
| SURBL | PostShiba, Tatami | Link and domain reputation checks | Links and domains found in messages | Varies |
| AbuseIPDB | PostShiba | IP reputation checks at signup | IP addresses | United States |
| Exa | Tatami | Signup screening: researches the domain of a new signup's email | Email domain | United States |
| TypeSafe | Tatami | Signup screening: scores the domain using that research | Email domain and public web research about it | Varies |

## Monitoring and operations

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| Better Stack | Bento, PostShiba, Tatami | Logging, error tracking, uptime monitoring, and incident alerting | Technical logs, IP address, request metadata, account identifiers | United States, European Union |
| New Relic | Bento | Application performance monitoring | Technical logs, account identifiers, diagnostic metadata | United States |
| Discord | All | Customer support and internal team communication | Support conversations, contact details, and account details discussed by our team | United States |

## Business operations

| Service provider | Products | Purpose | Customer data involved | Region |
| --- | --- | --- | --- | --- |
| Close | All | Sales CRM | Business contact details, communication history, account notes | United States |
| Google Workspace | All | Business email and documents | Business contact details, email content, message metadata | United States |
| Sanity | All | Website content management | Content we publish; no customer account data | United States |

## Changes to this page

We may add, replace, or remove subprocessors and service providers from time to time. We will update this page when we do.

## Contact us

If you have questions about this page or our subprocessors, please contact `support@bentonow.com`.
