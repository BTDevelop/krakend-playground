FROM grafana/grafana:8.5.0-50682pre-ubuntu

COPY ./datasources /etc/grafana/provisioning/datasources
COPY ./dashboards /etc/grafana/provisioning/dashboards
COPY ./krakend /var/lib/grafana/dashboards/krakend