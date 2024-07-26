FROM grafana/grafana:11.1.1-ubuntu

COPY ./datasources /etc/grafana/provisioning/datasources
COPY ./dashboards /etc/grafana/provisioning/dashboards
COPY ./krakend /var/lib/grafana/dashboards/krakend