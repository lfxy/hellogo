FROM 10.213.42.254:10500/caozhiqiang1/hpa-example:latest

COPY index1.php /var/www/html/
#COPY config/definition.json /etc/custom-metrics/
COPY config/config.json /var/cadvisor/
#LABEL io.cadvisor.metric.prometheus="/var/cadvisor/config.json"
LABEL io.cadvisor.metric.raw="/var/cadvisor/config.json"
