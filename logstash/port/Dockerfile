FROM logstash:7.6.2
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD port/pipeline/ /usr/share/logstash/pipeline/
#ADD config/ /usr/share/logstash/config/
EXPOSE 9500