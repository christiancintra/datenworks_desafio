FROM python:3.10.0a1-buster

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY /app .

CMD ["python", "hello_world.py"]