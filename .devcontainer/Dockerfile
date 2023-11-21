FROM --platform=amd64 ubuntu:14.04.5
RUN sudo apt-get update && sudo apt-get install -y git python libpython2.7 libatlas3-base
ADD ./pynaoqi-python2.7-2.5.5.5-linux64.tar.gz /
ENV PYTHONPATH=/pynaoqi-python2.7-2.5.5.5-linux64/lib/python2.7/site-packages
