FROM python:2.7

EXPOSE 8080

<<<<<<< HEAD
RUN pip install pip --upgrade \
        && pip install theonionbox
=======
RUN pip install pip --upgrade && pip install theonionbox
>>>>>>> d8c59cbbcceb4556f2b6eb05afe1479023652665

COPY theonionbox.cfg /usr/local/lib/python2.7/site-packages/theonionbox

ENTRYPOINT ["/usr/local/bin/theonionbox", "-c", "/usr/local/lib/python2.7/site-packages/theonionbox/theonionbox.cfg"]
