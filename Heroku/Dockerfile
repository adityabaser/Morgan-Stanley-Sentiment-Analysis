FROM python:3.7.2-stretch

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

CMD gunicorn app_final:app --bind 0.0.0.0:$PORT --reload