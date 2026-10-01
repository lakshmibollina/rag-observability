# RAG Observability

The operational layer most portfolios skip: tracing, cost, and quality monitoring for the Policy RAG Assistant.

## What this shows

- **Langfuse dashboard** — latency (p50/p95), cost per request, citation coverage.
- **Regression gating** — a GitHub Action that fails the build if eval accuracy drops.
- **Prompt-change experiment** — change a prompt, show the eval catching the regression (before/after table).

## Why it matters

This is the 70% of production AI work that nobody puts in their portfolio: knowing what your system costs, how slow it is, and when it got worse.

## Run it

```bash
pip install -r requirements.txt
```
