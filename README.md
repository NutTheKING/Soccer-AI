# Soccer-AI — Football Intelligence AI

Personal football research and prediction tracking project. Forecasts are uncalibrated statistical estimates, not guaranteed outcomes.

## Hosting
GitHub Pages supports a static preview only. The Python FastAPI application requires a separate backend host. For Render, use the included `render.yaml` and configure a persistent PostgreSQL database such as Neon. Never commit `.env` or any private credentials. Free tiers are subject to limits and change; optional OpenAI API usage is separately billed.

## Setup
See CLOUD-SETUP.md for deployment and Google OAuth configuration. Use `pip install -r requirements.txt` and `uvicorn app:app --host 127.0.0.1 --port 8000` for local development. Copy `.env.example` to `.env` and supply credentials locally.

The website is a prototype. Live data and login require provider configuration; forecasts must be evaluated on held-out matches before drawing conclusions about accuracy.
