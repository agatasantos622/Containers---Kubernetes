# Utiliza a imagem oficial do Nginx
FROM nginx:latest

# Remove a página padrão do Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia os arquivos HTML para o container
COPY html/ /usr/share/nginx/html/

# Expõe a porta padrão do Nginx
EXPOSE 80