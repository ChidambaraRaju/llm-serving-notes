# LLM Serving Notes

Study notes on serving and optimizing large language models, written while reading *Hands-On LLM Serving and Optimization*. This repo currently covers chapters 1 and 2.

The notes are a single HTML page with accompanying figures — no build step, no dependencies.

## What's covered

**Chapter 1 — Model serving and optimization**
- Anatomy of a model and the lifecycle from training to serving
- What serving engineers care about, and why optimization matters most for LLMs
- Four serving paradigms: on-device (edge), single-model service, multi-model service, and model serving platforms

**Chapter 2 — Large language model serving**
- Autoregressive generation and the decoder-only Transformer (tokenizer, decoder blocks, LM head)
- Attention and multi-head attention
- KV cache, prefill and decode
- Serving with vLLM vs Hugging Face Transformers, streaming, and batching

Each chapter ends with a recap and "Test yourself" questions, and the page closes with key numbers and a glossary.

## Repo structure

```
index.html   # the notes
images/      # figures referenced in the notes (fig-<chapter>-<n>.png)
```

## How to view

```bash
git clone https://github.com/ChidambaraRaju/llm-serving-notes.git
cd llm-serving-notes
open index.html   # or xdg-open / start, depending on your OS
```

## Note

These are personal study notes. The book itself is not included in this repo.
