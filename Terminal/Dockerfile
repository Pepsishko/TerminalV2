FROM httpd:2.4 AS Base
COPY . ./ /usr/local/apache2/htdocs/
# Copy everything

RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf