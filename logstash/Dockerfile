  
ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

LABEL maintainer="hedeqiang <hedeqiang@88.com>"

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json