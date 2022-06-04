FROM python:3.11.0b1

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

EXPOSE 5000
CMD ["python", "main.py"]

