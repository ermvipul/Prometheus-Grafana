# Prometheus-Grafana

In order to run the project

1. Preapre the prometheus.yml file & feed the necessary info like app port number .
2. Run the docker-compose.yml file using "docker compose up" command.
3. Prepare a django-app & install the django-prometheus package. Also, updates the middlewares.
4. Run the django-app & check for the api path <prometheus-xyzabc/metrics> .
5. Check proemtheus app whether its running or not (localhost:9090) & whether the targets are registered or not(localhost:9090/targets).
6. Check the grafana app running on http://localhost:3000/
7. For password & username use "admin"
8. Use the provided json to be used for dashboard import.
9. Check the dashboard logs
