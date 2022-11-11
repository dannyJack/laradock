FROM phpmyadmin

RUN mkdir /etc/phpmyadmin/uploads
RUN mkdir /etc/phpmyadmin/saves

LABEL maintainer="Bo-Yi Wu <appleboy.tw@gmail.com>"

# Add volume for sessions to allow session persistence
VOLUME /sessions

# We expose phpMyAdmin on port 80
EXPOSE 80
