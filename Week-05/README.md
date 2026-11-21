
# Week 5 - Token Economics: Cost and Rate-Limit Budgeting

## Aim
To develop a Python-based budgeting tool that estimates token consumption, API costs, and rate-limit requirements before building an LLM-powered feature.

## Learning Objectives
- Understand input, output, and total tokens.
- Calculate Requests Per Minute (RPM).
- Calculate Tokens Per Minute (TPM).
- Estimate daily and monthly token consumption.
- Calculate API usage costs.
- Apply safety margins.
- Check budget and rate-limit constraints.

## Tools & Technologies
- Python
- Google Colab

## Implementation
The budgeting tool accepts feature assumptions such as:
- Expected requests per day.
- Average input tokens per request.
- Average output tokens per request.
- Peak requests per minute.
- Input and output token prices.
- Monthly budget.
- Safety margin.

## Outcome
Created a reusable token budget planner that estimates usage and cost, checks rate limits, and evaluates whether a proposed LLM feature fits its configured budget.


