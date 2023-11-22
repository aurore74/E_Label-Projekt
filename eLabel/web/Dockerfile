FROM node:20
LABEL authors="wikom"
COPY _docker/start.sh /var/bootstrap/start.sh
RUN chmod 777 /var/bootstrap/start.sh
WORKDIR /home/node/app
CMD ["/var/bootstrap/start.sh"]
