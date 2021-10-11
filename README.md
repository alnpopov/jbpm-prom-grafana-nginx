# Проект jbpm-prom-grafana-nginx

Данный compose-файл запускает jbpm и grafana через nginx. Jbpmn настроен на работу с СУБД postgres.
Grafana настроена на работу с Prometheus. Внутри Grafana настроен Node Exporter Quickstart and Dashboard для отображение метрик из Prometheus.
Prometheus забирает метрики с host машины через node-exporter.

На сервере должны присутствовать docker и docker-compose
 - git clone https://github.com/alnpopov/jbpm-prom-grafana-nginx.git
 - docker-compose up
 - доступ к jbpm через http://{IP_ADDR}/business-central/
 логин wbadmin
 пароль wbadmin
 - доступ к grafana через http://{IP_ADDR}/grafana/
 логин admin
 пароль admin
