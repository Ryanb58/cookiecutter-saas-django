FROM python:3.5
ENV PYTHONUNBUFFERED 1

WORKDIR /app
# Requirements have to be pulled and installed here, otherwise caching won't work
ADD ./web/requirements.txt requirements.txt

RUN pip install -r requirements.txt
