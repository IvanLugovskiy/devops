FROM python:3.12-slim
RUN apt-get update && apt-get install -y wget && rm -rf /vat/lib/apt/lists/*
WORKDIR /app
COPY app.py .
CMD ["python", "app.py"]
