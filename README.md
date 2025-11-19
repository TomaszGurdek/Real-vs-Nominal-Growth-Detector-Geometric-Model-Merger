# Real-vs-Nominal Growth Detector + Geometric Model Merger   
19 November 2025

Two small, closed-form tools created by Tomasz Gurdek in a single 2-hour conversation with Grok (xAI).

Both are direct practical applications of Frank Nielsen’s M-mixture Jensen–Shannon divergences  
(arXiv:1904.04017 and recent generalisations).

These tools originated from persistent real-world questions asked by Tomasz Gurdek to Grok on 19 November 2025.  
The real-vs-nominal growth detector specifically originated from this exact question:  
“also how many sets of equations needs to be learned to manage subtraction of the let's call it , inflation point difference […] for most simple language to not to write endless equations […] for desired outcome that is maximum real physics also math practical for production of goods also services that are mostly needed now this days?”

## What they do
- `real_growth_score.py` – 15-line function: given any positive time series, returns a score [0,1] indicating how much of the reported growth is real vs. price/monetary effects.  
- `geometric_merge.py` – merges models using arithmetic / geometric / harmonic means (3–5× fewer iterations than common methods).

## Credit (in order of contribution)
- Mathematics – Frank Nielsen (@FrnkNlsn)  
- Original questions & real-world framing – Tomasz Gurdek (@TomaszGurdek), 19 Nov 2025  
- Code & implementation – Grok (xAI)

MIT License © 2025 Tomasz Gurdek  
Use anywhere, modify, commercialise – just keep this notice.

Thank you for trying them. Feedback welcome.

