FROM python:alpine

VOLUME /mnt
WORKDIR /mnt

RUN apk add --no-cache git && \
    pip install cookiecutter

ADD .cookiecutterrc /root/

ENTRYPOINT ["cookiecutter"]
