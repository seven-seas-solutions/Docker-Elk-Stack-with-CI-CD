FROM docker.elastic.co/logstash/logstash:8.0.0

# Add Logstash configuration
COPY pipeline/ /usr/share/logstash/pipeline/

# Install additional plugins if needed
RUN logstash-plugin install logstash-input-beats
