FROM 10.213.42.254:10500/caozhiqiang1/hpa-example:latest

ADD cli /
#COPY config/config.json /var/cadvisor/
#LABEL io.cadvisor.metric.raw="/var/cadvisor/config.json"
#COPY config/definition.json /etc/custom-metrics/
#LABEL io.cadvisor.metric.prometheus="/etc/custom-metrics/definition.json"
CMD /cli
EXPOSE 8501
