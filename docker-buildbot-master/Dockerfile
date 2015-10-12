FROM phusion/baseimage:0.9.17

CMD ["/sbin/my_init"]

RUN apt-get update && apt-get -y dist-upgrade
RUN apt-get install -y python-pip libpython-dev
RUN pip install buildbot
