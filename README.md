# Loki-Grafana

we are interest in grafana/loki-stack

helm show values grafana/loki-stack > /temp/loki-stack-values.yaml

vi /temp/loki-stack-values.yaml

helm install loki-stack grafana/loki-stack --values /temp/loki-stack-values.yaml
