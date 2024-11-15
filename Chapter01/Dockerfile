FROM python:3.14.0a1

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

EXPOSE 5000
CMD ["python", "main.py"]

