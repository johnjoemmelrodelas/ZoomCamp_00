FROM python:3.10

WORKDIR /app

COPY requirements.txt .
COPY pipeline.py pipeline.py

RUN pip3 install -r requirements.txt

EXPOSE 8080

ENTRYPOINT [ "python", "pipeline.py" ]