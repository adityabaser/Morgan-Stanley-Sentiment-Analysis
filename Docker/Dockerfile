FROM python:3.7.2-stretch

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

EXPOSE 5000

ENTRYPOINT  ["python"]

CMD ["project/app_final.py"]