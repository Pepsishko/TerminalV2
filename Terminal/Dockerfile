FROM php:7.0-apache
# Copy everything
COPY . ./
# Restore as distinct layers
RUN dotnet restore

RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf