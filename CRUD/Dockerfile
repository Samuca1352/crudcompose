# Use uma imagem oficial do PHP com Apache pré-instalado
FROM php:8.1-apache

WORKDIR "/app"
# Instala as extensões PHP necessárias para se conectar ao MySQL
RUN docker-php-ext-install pdo_mysql mysqli

# Copia os arquivos da sua aplicação (do diretório atual, 'CRUD') 
# para o diretório raiz do Apache no container (/var/www/html)
COPY . /var/www/html/