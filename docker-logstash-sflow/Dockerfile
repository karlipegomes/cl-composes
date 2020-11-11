FROM docker.elastic.co/logstash/logstash:7.10.0

RUN /usr/share/logstash/bin/logstash-plugin install logstash-codec-sflow

COPY 10-sflow.conf /usr/share/logstash/pipeline/logstash.conf

EXPOSE 6343/udp
