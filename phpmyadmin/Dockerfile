FROM phpmyadmin

RUN mkdir /etc/phpmyadmin/uploads
RUN mkdir /etc/phpmyadmin/saves

LABEL maintainer="Bo-Yi Wu <appleboy.tw@gmail.com>"

# Add volume for sessions to allow session persistence
ARG SESSION_PATH="sessions"
VOLUME /${SESSION_PATH}

# We expose phpMyAdmin on port 80
EXPOSE 80
