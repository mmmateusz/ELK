# ELK
Elasticsearch, Logstash, Kibana with Filebeat example. To start run `docker-compose up -d` in root directory of the repository. This will setup ELK stack collecting docker logs through Filebeat.

* CAdvisor - monitoring of docker engine containers
* Node exporter - monitoring of VM resources
* Blackbox exporter - monitoring of Kibana/Elasticsearch URLs

Available services:

 * Elasticsearch: 192.168.44.44:9200
 * Logstash:  192.168.44.44:4560 
 * Kibana: 192.168.44.44:5601