FROM ubuntu:latest

RUN apt-get update \
    && apt-get install -y python3

WORKDIR /app

COPY "my_csv_reader.py" /app
COPY "housing.data" /app

CMD ["python3","-u","./my_csv_reader.py"]
