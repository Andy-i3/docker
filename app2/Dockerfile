FROM nodejscn/node

ENV VERSION 1.0.0

LABEL mantainer=a0z9@rambler.ru

WORKDIR /var/www/wapp

COPY wapp.js .

VOLUME /var/www/wapp

EXPOSE 8080

ENTRYPOINT ["node","wapp.js"]


