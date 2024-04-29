FROM python:3.10

WORKDIR /app

COPY . .

RUN pip3 install -r requirements.txt

##ENV DATABASE_URL =

EXPOSE 8000

CMD ["python3", "main.py"]