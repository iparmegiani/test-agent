# Inventory Agent Prototype

## Goal
Build a Python agent that answers natural language questions 
against inventory data using Azure OpenAI and Anthropic.

## Environment
- AI provider switchable via environment variable
- Anthropic API key for local development
- Azure OpenAI endpoint for work environment
- Secrets stored in .env file locally, never hardcoded
- Plain Python, pandas for data handling

## Patterns
- Never hardcode API keys
- Use .env for local secrets
- Keep code provider agnostic where possible

## Current State
- Fresh project
- Building inventory agent prototype
- Testing natural language to pandas query generation