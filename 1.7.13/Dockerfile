FROM python:2-slim
MAINTAINER Maciej Strzelecki <maciej.strzelecki@gmail.com>

RUN apt-get update && apt-get install -y groff-base --no-install-recommends && rm -rf /var/lib/apt/lists/*

ENV AWSCLI_VERSION 1.7.13

RUN pip install awscli==$AWSCLI_VERSION

ENV PAGER cat

ENTRYPOINT ["aws"]
CMD ["help"]
