# Dockerfile for Backend Service
FROM python:3.12-slim
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
COPY src /app
EXPOSE 5001
CMD ["python", "main.py"]
