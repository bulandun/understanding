# Understanding LLMs

An interactive, three-dimensional explainer showing how a large language model produces one token at a time.

## What it demonstrates

- text being divided into tokens and represented as numerical vectors
- attention changing how tokens influence one another
- repeated transformer-layer calculations
- a probability distribution over possible next tokens
- the selected token returning to the context so the loop can continue
- concise contrasts between human experience and LLM computation

The geometry and probabilities are illustrative. This is a learning tool, not a live view inside a production language model and not a claim that an LLM thinks like a human.

## Files

- `index.html` — standalone version that runs in a browser
- `src/llm-next-token-lab.html` — editable source fragment

## Run locally

Open `index.html` directly, or serve the repository with any static web server.

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
