FROM prom/prometheus

COPY ./prometheus.yaml /etc/prometheus/

RUN build -t prometheus .
RUN run -p 9090:9090 prometheus
