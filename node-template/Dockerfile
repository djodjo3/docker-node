FROM noding

MAINTAINER Claude-Arnaud PERROT "claude-arnaud.perrot@prestashop.com"

RUN git clone git@github.com:djodjo3/node-sample.git /opt/node-sample/

RUN cd /opt/node-sample/ && npm install

EXPOSE 8080

CMD ["node", "/opt/node-sample/index.js"]


