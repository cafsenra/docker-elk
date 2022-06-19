ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

# Add config file
COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
