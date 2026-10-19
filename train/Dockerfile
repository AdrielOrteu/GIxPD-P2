FROM python:3.11-slim
WORKDIR /app
COPY requirements-train.txt .
RUN pip install --no-cache-dir -r requirements-train.txt
COPY main-train.py .
ENV MODEL_PATH=/data/model.plk
CMD ["python", "main-train.py"]
