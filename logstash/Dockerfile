FROM logstash:8.10.1

COPY pipelines.yml /usr/share/logstash/config/pipelines.yml
COPY service_logs.conf /usr/share/logstash/pipeline/service_logs.conf

EXPOSE 6000 9600