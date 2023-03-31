FROM fluent/fluentd:v1.16-debian
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "4.3.1"]
USER fluent