# Utiliza a imagem oficial do Apache
FROM httpd:latest

# Remove os arquivos padrão
RUN rm -rf /usr/local/apache2/htdocs/*

# Copia os arquivos HTML para o container
COPY html/ /usr/local/apache2/htdocs/

# Expõe a porta padrão do Apache
EXPOSE 80