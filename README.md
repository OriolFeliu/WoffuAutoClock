# WoffuAutoClock

Automates employee check-ins and check-outs in **Woffu** between specified dates. This Python script generates weekday attendance records with your specified times and dates and can optionally sync them via the Woffu API.

---

## Features

- Automatically generates attendance records between two dates.
- Supports weekdays-only scheduling.
- Configurable check-in (09:00) and check-out (17:00) times.
- API integration with Woffu for automated submission.
- Lightweight and easy to customize.

---

## Requirements

- Python 3.8 or higher
- `requests` library

Install dependencies using pip:

```bash
pip install requests
