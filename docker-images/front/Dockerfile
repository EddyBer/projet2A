FROM node:lts-alpine

# définit le dossier 'app' comme dossier de travail
WORKDIR /vue-front

COPY ./docker-images/front/entrypoint.sh /usr/local/bin

RUN chmod +x /usr/local/bin/entrypoint.sh

ENTRYPOINT [ "/usr/local/bin/entrypoint.sh"]