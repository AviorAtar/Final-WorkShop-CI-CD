FROM python:3.9-slim

WORKDIR /app

COPY . /app

RUN pip install flask

EXPOSE 80:80

ENV NAME World

CMD ["python", "app.py"]
