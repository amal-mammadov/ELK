# elk
Files related to the ELK stack (ElasticSearch, Logstash, Kibana), such as json files for configuration, logstash filters, filebeat configurations, etc.
D. Murphy

02-beats-input.conf : This is the FileBeat input configuration for Logstash as created under the "Configure Logstash" section of - 
  https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-14-04

10-syslog-filter.conf : This is the generic syslog input configuration for Logstash as created under the "Configure Logstash" section of - 
  https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-14-04

30-elasticsearch-output.conf : This is the ElasticSearch output configuration for Logstash as created under the "Configure Logstash" section of - 
  https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-14-04

11-iis-filter.conf : This is the filter created to parse the W3C logs from IIS, with all options selected for logging.

12-kiwi-filter.conf : This is the filter created to parse Kiwi SysLog Server messages into LogStash

filebeat-index-template.json : This file is used in the "Load Filebeat Index Template in Elasticsearch" of - 
  https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-14-04
The link referenced in the walkthrough was not functioning, so I've stored the file here for future use after hunting for it.

topbeat.template.json : A functional topbeat configuration template. The guide I used did not properly resolve but I found and used this one.
