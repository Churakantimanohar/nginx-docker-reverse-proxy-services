FROM python:3.11-slim

WORKDIR /app

# Install Flask the simple way
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

CMD ["python", "app.py"]
