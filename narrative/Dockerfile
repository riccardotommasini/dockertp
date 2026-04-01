FROM python:3.12-slim

WORKDIR /app

ENV PYTHONUNBUFFERED=1

COPY requirements.txt ./requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY server.py ./server.py

CMD ["python", "server.py"]
