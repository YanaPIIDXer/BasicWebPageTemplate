FROM nginx:stable

ADD ./Config /etc/nginx/conf.d

ADD ./Sources /var/www/html
RUN chmod 755 /var/www/html -R
WORKDIR /var/www/html
