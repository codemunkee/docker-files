FROM ubuntu:14.04
MAINTAINER Russ Nealis <codemunkee@gmail.com>
RUN apt-get update && apt-get install -y \
    python \
    python-dev\
    python-pip\
    git
RUN git clone https://github.com/codemunkee/emelbee &&\
    cd /emelbee && python setup.py install
CMD ["/emelbee/bin/emelbee_api"]
