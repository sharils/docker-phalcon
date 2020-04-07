FROM node:12.3.1-alpine
MAINTAINER sharils <sharils@users.noreply.github.com>

RUN npm install --global prettier@2.0.2 && npm cache --force clean

ENTRYPOINT ["prettier"]
