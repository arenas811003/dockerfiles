FROM docker.elastic.co/elasticsearch/elasticsearch:7.6.2

ADD ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
# ADD ./ /usr/share/elasticsearch/data

# ENV ES_JAVA_OPTS="-Xmx512m -Xms512m"
# ENV ELASTIC_PASSWORD: changeme
# ENV discovery.type="single-node"

EXPOSE 9200