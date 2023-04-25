ARG ELASTIC_VERSION

FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

ADD ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml:ro,z
ADD ./ /usr/share/elasticsearch/data,z

ENV ES_JAVA_OPTS="-Xmx512m -Xms512m"
ENV ELASTIC_PASSWORD: changeme
ENV discovery.type="single-node"

EXPOSE 9200