
# fluentd/Dockerfile with elastic search plugin
FROM fluent/fluentd:v1.14.5-1.0
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
#RUN ["gem", "install", "fluent-plugin-splunk-hec"]
RUN ["gem", "install", "fluent-plugin-splunk-enterprise"]