FROM python:2
MAINTAINER Maciej Strzelecki <maciej.strzelecki@gmail.com>

ENV AWSCLI_VERSION 1.7.12

RUN pip install awscli==$AWSCLI_VERSION

ENTRYPOINT ["aws"]
