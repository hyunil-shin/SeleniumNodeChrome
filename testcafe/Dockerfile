FROM anyonecantest/nodechrome:3.141.59-20200515
MAINTAINER hyunil.shin <hyunil.shin@nhn.com>

USER root

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt-get -y install nodejs
RUN apt-get install -y ffmpeg

###
USER seluser
