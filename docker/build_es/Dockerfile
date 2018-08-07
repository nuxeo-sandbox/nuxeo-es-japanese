FROM docker.elastic.co/elasticsearch/elasticsearch:5.6.9

RUN bin/elasticsearch-plugin remove x-pack
RUN bin/elasticsearch-plugin install analysis-kuromoji
RUN bin/elasticsearch-plugin install analysis-icu
