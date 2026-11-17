# Multi-Agent Marketplace Negotiator

### AI Agents Assignment — Used PlayStation 5 Marketplace

## Project Overview

This project implements a five-agent AI negotiation system using the Anthropic Claude Agent SDK.

The system simulates a marketplace negotiation for a used PlayStation 5 Disc Edition with a controller.

## Five-Agent Architecture

1. **Coordinator:** Manages delegation and workflow.
2. **Researcher:** Searches for market information using WebSearch.
3. **Buyer:** Negotiates within a maximum budget of $420.
4. **Seller:** Negotiates with a minimum acceptable price of $400.
5. **Referee:** Independently audits negotiation decisions and outcomes.

Only the Researcher has WebSearch permission.

## Key Features

- Multi-agent task delegation
- Buyer–Seller negotiation
- Market research integration
- Negotiation offer validation
- Six-round maximum negotiation limit
- SDK event logging
- Independent Referee validation

## Experimental Results

| Experiment | Result |
|---|---|
| Tuning V1 | No agreement |
| Tuning V2 | $400 agreement |
| Tuning V3 | $410 agreement |
| SDK Run 1 | $405 agreement |
| SDK Run 2 | $401 agreement |

Both final SDK negotiations received VALID Referee verdicts.

## Technologies

- Python
- Anthropic Claude Agent SDK
- Jupyter Notebook
- Google Colab
- WebSearch

## Limitations

Market research findings are low-confidence leads and were not independently verified against a complete sold-listing dataset. Live execution requires an Anthropic API key.

## Project Files

- Jupyter Notebook — implementation and experiments
- Executive Summary — project overview
- Architecture Diagram — five-agent workflow

## Author

AI Agents Assignment Project
