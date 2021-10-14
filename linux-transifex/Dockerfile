FROM debian:buster-slim
MAINTAINER yuzu
ENV DEBIAN_FRONTEND=noninteractive
RUN adduser -u 1027 -D -s /bin/bash yuzu && apt-get update && apt-get -y full-upgrade
RUN apt-get install -y git p7zip-full libqt5opengl5-dev qtmultimedia5-dev qttools5-dev qttools5-dev-tools python3-pip cmake
RUN pip3 install transifex-client
USER 1027
