ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}
RUN logstash-plugin install logstash-input-azure_event_hubs
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
