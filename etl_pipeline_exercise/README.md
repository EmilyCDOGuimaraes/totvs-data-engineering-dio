# ETL Pipeline with Python — Santander Dev Week 2023

A simple, end-to-end ETL (Extract, Transform, Load) pipeline built in Python as part of the TOTVS Fundamentos de Engenharia de Dados e Machine Learning bootcamp on DIO.

---

## What it does

This project demonstrates the core ETL flow using Python:

- **Extract** — loads user data (name, account, card) into a structured format using pandas
- **Transform** — applies a personalised marketing message generation function to each user, simulating an AI-powered content layer
- **Load** — exports the enriched user data to a JSON file, completing the pipeline cycle

---

## Why this matters

ETL is foundational to data engineering. This project strips the concept down to its essentials: get data, do something meaningful with it, put it somewhere useful. No unnecessary complexity — just a clean, readable pipeline that anyone can follow and extend.

---

## Tech stack

- Python 3
- pandas
- json
- Google Colab

---

## How to run

1. Open `ETL_pipeline.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells in order
3. Check `output.json` for the results

---

## Project structure

```
├── ETL_pipeline.ipynb   # Main notebook with ETL pipeline
├── output.json          # Generated output (created on run)
└── README.md
```

---

## Notes

The original project used the Santander Dev Week 2023 API (now discontinued) and OpenAI GPT-4. This version adapts the Extract stage to use in-code data and the Transform stage to use a local message generation function — consistent with the official guidance provided by DIO for handling API unavailability.

The ETL flow is identical. The tools are simpler. The learning is the same.

---

*Part of the TOTVS Fundamentos de Engenharia de Dados e Machine Learning bootcamp — DIO, 2026*

---
