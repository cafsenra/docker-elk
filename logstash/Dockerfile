ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION}


# Add config file
COPY ./config/logstash.yml /usr/share/logstash/config/logstash.yml

# Add pipeline file
COPY ./pipeline /usr/share/logstash/pipeline

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
