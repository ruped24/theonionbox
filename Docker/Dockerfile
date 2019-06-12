FROM python:2.7
LABEL maintainer="ruped24@gmail.com"

RUN pip install \
        pip --upgrade \
        && pip install \
        theonionbox

ADD theonionbox.cfg /usr/local/lib/python2.7/site-packages/theonionbox

EXPOSE 8080

ENTRYPOINT ["/usr/local/bin/theonionbox", "-c", "/usr/local/lib/python2.7/site-packages/theonionbox/theonionbox.cfg"]
