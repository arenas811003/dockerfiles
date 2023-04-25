ARG ELASTIC_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:${ELASTIC_VERSION}

ADD ./config/kibana.yml /usr/share/kibana/config/kibana.yml:ro,z

EXPOSE 5601
