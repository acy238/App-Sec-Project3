FROM prom/prometheus

COPY ./prometheus.yaml /etc/prometheus/prometheus.yaml

RUN build -t prometheus .
# Instructions for running this container is written in the file: part3/Prometheus.txt 
# RUN run -p 9090:9090 prometheus
