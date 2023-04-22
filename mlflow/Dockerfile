FROM python:3.10-slim-buster
RUN pip install --upgrade pip
RUN pip install psycopg2-binary
COPY requirements.txt /tmp
RUN pip install -r /tmp/requirements.txt
