Logs. Fluentd + Elastic + Grafana
Métricas. Prometheus + Grafana
Trazabilidad. Jaeger + Elastic + Grafana


En el host debe ejecutarse este código antes de subir el `docker-compose up` para subir la memoria virtual de Elasticsearch:
[sudo sysctl -w vm.max_map_count=262144](https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html)

