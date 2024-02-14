# prometheus-stack-docker-compose


## Iniciar o container do prometheus local - o arquivo prometheus.yml precisa estar criado.
docker run --name prometheus --rm -d -p 9090:9090 -v /home/norman-hughes/Documentos/Norman/Grafana/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml  prom/prometheus

## atualizar contianer
Docker container restart prometheus

