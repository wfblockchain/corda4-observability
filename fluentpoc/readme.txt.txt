This is for fluentd - Splunk, Elastic search and Prometheous to Grafana POC
You should finish the initial setting up observability (all the steps mentionmed in readme.md)
Steps
1. Create fluentd folder under mynetwork
2. copy Dockerfile and fluent.conf files to fluentd
3. Copy   docker-compose-fluent-prometheus-splunk.yml file to mynetwork
4. run commamnd docker compose -f mynetwork/docker-compose-fluent-prometheus-splunk.yml up -d