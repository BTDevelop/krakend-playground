FROM grafana/grafana:9.4.0-beta1-ubuntu

COPY ./datasources /etc/grafana/provisioning/datasources
COPY ./dashboards /etc/grafana/provisioning/dashboards
COPY ./krakend /var/lib/grafana/dashboards/krakend