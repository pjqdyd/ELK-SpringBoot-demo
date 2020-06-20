### 在Docker中安装ELK (ElasticSearch, Logstash, Kibana)

 sudo chown -R root:root elk-docker/
 
 sudo chmod -R 777 elk-docker/
 
 
 max virtual memory areas vm.max_map_count [65530] is too low, increase to at...
 
 vi /etc/sysctl.conf
 
 vm.max_map_count=655360
 
 sysctl -p