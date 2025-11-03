# Usar a imagem base do Python
FROM python:3.9-slim

# Instalar dependências
RUN pip install requests gpxpy

# Copiar o código do simulador
WORKDIR /app
COPY simulator.py .
COPY ../trail_route.gpx .

# Comando para iniciar o simulador
CMD ["python", "simulator.py"]