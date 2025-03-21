# HFModel - FastAPI LLM Text Generation API

This is a FastAPI-based API for generating text using Hugging Face models.

## Features
- Generate text based on a prompt.
- Customize the length and creativity of the output.
- Supports models like DistilGPT-2, Mistral 7B, and more.

## Setup
1. Clone the repository:
   \\\ash
   git clone https://github.com/waleedmaqsood20/hfmodel.git
   \\\
2. Install dependencies:
   \\\ash
   pip install -r requirements.txt
   \\\
3. Run the app:
   \\\ash
   uvicorn app.main:app --reload
   \\\

## Deployment
Deploy this app on Fly.io, Vercel, or Render. See the [deployment guide](#) for details.

## API Endpoints
- \GET /\: Root endpoint with API information.
- \POST /generate\: Generate text based on a prompt.
- \GET /health\: Health check endpoint.
