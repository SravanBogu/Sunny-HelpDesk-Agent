# Sunny-HelpDesk-Agent 
## Description: Azure AI Foundry Enterprise Helpdesk Triage Agent

A sanitized proof of concept demonstrating how Azure AI Foundry can classify
enterprise HR and IT support requests, assign urgency, recommend routing, and
enforce human escalation for sensitive or high-risk scenarios.

## Business problem
Support teams receive unstructured requests through multiple channels. Manual
triage delays response time and produces inconsistent routing.

## POC outcome
The agent returns structured JSON containing category, priority, summary,
recommended queue, escalation decision, and rationale.

## Target architecture
Copilot Studio or a web/Teams user experience → secure API or Power Automate →
Azure AI Foundry triage agent → Dataverse, Dynamics 365, or service desk system.

## Data safety
All policy documents, tickets, names, and test cases are fictional. No client,
employee, or confidential data is included.
