# Docker Configuration

## Dockerfile

```dockerfile
FROM python:3.11-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

CMD ["uvicorn", "main:app", "--host", "0.0.0.0"]
```

## Build & Run

```bash
docker build -t ml-app .
docker run -p 8000:8000 ml-app
```