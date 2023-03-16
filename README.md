# OpenSearch_Logstash_Filebeat_test
Stack Filebeat -> Logstash -> OpenSearch

Test to deploy OpenSearch and create a stack with Logstash and Filebeat. Docker Compose was used as an automated tool for installation and management.

Opensearch is organized as a cluster with two nodes. Also deployed OpenSearch Dashboards.

Stack components versions: 
- Filebeat: 8.6.2
- Logstash: 8.6.1
- OpenSearch (with Opensearch Dashboards): 2.6.0

System: Ubuntu 22.04.2 LTS.

Attached configuration files, screen forms and a test nginx access log file (in `tar` archive).

Dashboard screenshot is a histogram of server response codes to unique hosts distribution.
