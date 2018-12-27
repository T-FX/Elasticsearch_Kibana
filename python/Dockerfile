FROM python:3.6.7
ADD requirements.txt /requirements.txt
RUN pip install -r /requirements.txt \
    && apt-get update \
    && apt-get install telnet
