# AI Agent Assignment – PPT Generator

## Project Overview
This project automates the generation of a PowerPoint presentation (`.pptx`) from Markdown answers to three AI agent assignment questions:

1. Multi-tenant scaling (OpenClaw vs Manus)  
2. Improving Claude Code efficiency  
3. Cognitive limits and extending human problem-solving  

The workflow parses Markdown files and converts them into slides automatically using Python.

---

## Dependencies

- Python 3.9+  
- [`python-pptx`](https://python-pptx.readthedocs.io/en/latest/)

Install with:

```bash
pip install python-pptx
```
---
## Usage

1. Copy prompts into Claude Code CLI, it will generate corresponding markdown files.
2. Place your Markdown answers in outputs/.
3. Run the generator script: `python generate.py`
4. The PPTX will be saved in presentation.pptx.
