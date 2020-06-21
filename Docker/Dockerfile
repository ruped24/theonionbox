FROM python:3.6
LABEL maintainer="ruped24@gmail.com"

RUN pip install      \
        pip --upgrade \
        && pip install \
        theonionbox

COPY theonionbox.cfg /usr/local/lib/python3.6/site-packages/theonionbox

EXPOSE 8080

ENTRYPOINT ["/usr/local/bin/theonionbox", "-c", "/usr/local/lib/python3.6/site-packages/theonionbox/theonionbox.cfg"]
