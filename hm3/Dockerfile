FROM python:latest

WORKDIR /app

COPY memory_info.py .
COPY requirements.txt .

RUN python3 -m pip install psutil -U

RUN mkdir -p data

ENTRYPOINT ["python3", "memory_info.py"]