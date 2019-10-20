FROM logstash:7.4.0

COPY ./logstash.conf ./config

CMD ["logstash", "-f", "./config/logstash.conf"]