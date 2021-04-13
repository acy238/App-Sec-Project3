FROM prom/prometheus:latest

COPY ./prometheus.yaml /etc/prometheus/

RUN build -t my-prometheus .
RUN run -p 9090:9090 my-prometheus
