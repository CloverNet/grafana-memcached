	FROM grafana/grafana:latest

	#ENV GF_SECURITY_ADMIN_PASSWORD jyxaizw

	COPY grafana.ini /etc/grafana/grafana.ini
	COPY Prometheus.yaml /etc/grafana/provisioning/datasources/prometheus.yaml
	COPY Memcached.yaml /etc/grafana/provisioning/dashboards/memcached.yaml
	COPY Memcached.json /etc/grafana/provisioning/dashboards/memcached.json
	
	EXPOSE 3000

	