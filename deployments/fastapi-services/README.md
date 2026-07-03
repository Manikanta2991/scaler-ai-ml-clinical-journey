# FastAPI Services

## Overview

REST APIs for model serving and inference.

## Endpoints
- `/predict` - Make predictions
- `/health` - Health check
- `/models` - List available models

## Running
```bash
uvicorn main:app --reload
```