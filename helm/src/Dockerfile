FROM python:3.12.0a5-slim

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

ENTRYPOINT ["python3", "./check_helm_charts.py"]
