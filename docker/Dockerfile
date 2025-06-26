FROM python:3.13.4-alpine3.22

ENV TZ=Asia/Tokyo
ENV PYTHONPYCACHEPREFIX=/tmp/__pycache__

WORKDIR build
COPY . .
RUN pip install -r requirements.txt

WORKDIR /app/src
