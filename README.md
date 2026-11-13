# Creatio-accounting-ai-integrations
Public portfolio case study, subject to employer permission

# Creatio AI Accounting Integrations: Xero & QuickBooks

## Overview

This project documents my hands-on work developing two accounting-system integrations with Creatio Freedom UI and Creatio AI Agents.

The integrations connect Xero and QuickBooks Online through REST APIs and OAuth 2.0 authentication, allowing accounting information to be retrieved and made accessible through conversational AI agents.

The project demonstrates the combination of API integration, business-process automation, data retrieval and AI-powered interaction.

## Integrations

### 1. Xero Integration Agent

**Creatio components:**
- Business Process: `UsrXeroAPIGetInvoices`
- AI Skill: `UsrXeroDataSkill`
- AI Agent: `UsrXeroAgent`

**Implemented functionality documented:**
- Xero REST API integration.
- OAuth 2.0 authentication configuration.
- Tenant ID retrieval and configuration.
- Invoice retrieval through the Xero API.
- Business-process execution and structured response handling.
- AI Skill and conversational agent configuration.
- API response testing and troubleshooting.

**Invoice endpoint:**
`GET /api.xro/2.0/Invoices`

### 2. QuickBooks Online Integration Agent

**Creatio components:**
- Business Process: `UsrQuickBooksExpIntegrationAgent`
- AI Skill: `UsrQuickBooksDataSkill`
- AI Agent: `UsrQuickBooksAgent`

**Implemented functionality documented:**
- QuickBooks Online REST API integration.
- OAuth 2.0 authentication configuration.
- Invoice queries using the QuickBooks Query API.
- Creatio business-process configuration.
- AI Skill integration with the business process.
- Conversational AI Agent configuration.
- API testing and troubleshooting.

**Example query:**
`SELECT * FROM Invoice`

## Technical Architecture

The integrations follow a general workflow:

1. External accounting platform.
2. OAuth 2.0 authentication.
3. Creatio REST web service.
4. Creatio business process.
5. Creatio AI Skill.
6. Creatio AI Agent.
7. Conversational response.

## Technologies & Tools

- Creatio Freedom UI
- Creatio Studio
- Creatio AI Agents
- Creatio AI Skills
- REST APIs
- OAuth 2.0
- Xero API
- QuickBooks Online API
- Postman
- JSON data extraction
- Business-process automation

## Testing

The documentation covers:
- API authentication and connection testing.
- Successful API responses.
- Invoice retrieval.
- Business-process execution.
- JSON response handling.
- AI Agent interaction.
- Troubleshooting authentication and empty-response issues.

## Future Improvements

- Scheduled invoice synchronisation.
- Updating existing invoice records.
- Customer and payment data retrieval.
- Integration logging and monitoring.
- Dedicated invoice visualisation in Creatio.

## Project Scope & Transparency

This repository is a sanitised technical case study of my professional integration work.

It documents the architecture, configuration, implementation responsibilities and testing described in the project documentation. It does not claim that future improvements were implemented.

Proprietary source code, credentials, customer information and confidential company configuration are excluded.

## My Contribution

My work involved exploring and testing external APIs, configuring authentication and web services, implementing Creatio business-process logic, working with AI Skills and Agents, and testing the integration workflows.

**Author:** Faten Helmi
