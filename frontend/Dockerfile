# Usar a imagem base do Nginx
FROM nginx:alpine

# Criar um diretório para o arquivo GPX (Create a directory for the GPX file)
RUN mkdir -p /usr/share/nginx/html/gpx

# Copiar os arquivos do frontend (HTML, imagens, etc.) para o diretório público do Nginx
COPY frontend/ /usr/share/nginx/html/
# Copiar o arquivo GPX do diretório do simulador para a pasta gpx
COPY simulator/trail_route.gpx /usr/share/nginx/html/gpx/trail_route.gpx