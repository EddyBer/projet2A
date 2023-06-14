# Base image
FROM node:18

# Create app directory
WORKDIR /usr/src/app

COPY ./docker-images/back/entrypoint.sh /usr/local/bin

RUN chmod +x /usr/local/bin/entrypoint.sh

ENTRYPOINT [ "/usr/local/bin/entrypoint.sh"]