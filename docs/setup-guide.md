# Setup Guide

## Prerequisites

- Python 3.9 or higher
- pip (Python package manager)
- Git

## Environment Variables

Copy `src/.env.example` to `.env` and fill in:

```
IBM_BOB_API_KEY=your_bob_api_key_here
DATA_PATH=./data/port_data.csv
MODEL_PATH=./models/
```

## Installation

```bash
# 1. Clone the repo
git clone https://github.com/JaiminShah123/bob-ai-hackathon-portmind-ai.git
cd bob-ai-hackathon-portmind-ai

# 2. Create virtual environment
python -m venv venv
venv\Scripts\activate

# 3. Install dependencies
pip install -r src/requirements.txt
```

## Running the Project

```bash
streamlit run src/app.py
```

The app will open at `http://localhost:8501`

## How to Verify It's Working

1. Dashboard loads with port congestion overview
2. Predictions display on the screen

## Troubleshooting

| Error | Solution |
|---|---|
| `ModuleNotFoundError` | Run `pip install -r src/requirements.txt` |
| `Port 8501 already in use` | Run with `--server.port 8502` |