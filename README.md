# Future Commodities Lab

Open-source education for:
- Physical commodity trading (process, contracts, logistics, hedging, risk)
- Systematic commodity trading (data, signals, backtests, risk, research)

## Who this is for
Students, analysts, junior traders, and builders who want practical, reproducible learning.

## What’s inside
- `/docs/physical`: real-world workflows, checklists, and templates
- `/docs/systematic`: research notes and strategy walkthroughs
- `/src/fc`: a small Python library for commodity strategy research
- `/notebooks`: end-to-end examples

## Quickstart (systematic)
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python -m fc.demo_momentum

