# Usar a imagem base do Nginx
FROM nginx:alpine

# Criar um diretório para o arquivo GPX (Create a directory for the GPX file)
RUN mkdir -p /usr/share/nginx/html/gpx

# Copiar os arquivos do frontend para o diretório público do Nginx (Copy the frontend files to the Nginx public directory)
COPY . /usr/share/nginx/html/
# Copiar o arquivo GPX do diretório do simulador (Copy the GPX file from the simulator directory)
COPY ../simulator/trail_route.gpx /usr/share/nginx/html/gpx/trail_route.gpx