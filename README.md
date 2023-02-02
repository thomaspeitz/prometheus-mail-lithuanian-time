# Prometheus monitoring using docker compose

Example repository based on - https://github.com/PhiCygni/prometheus-plus-altermanager-mailhog-smtp-docker-compose

Explains how to send emails in different timezones

Tags - Prometheus, timezone, alertmanager, local time, .StartsAt.Local.Format

# Usage

**To build and start all containers:**

>$ docker-compose up

# Web UI and open ports

| Open ports | Description                    | URL                    |
| ---------- | ------------------------------ | ---------------------- |
| 9090       | Prometheus Web UI              | http://localhost:9090  |
| 9093       | Prometheus Alertmanager Web UI | http://localhost:9093  |
| 8025       | Mailhog Web UI                 | http://localhost:8025  |
| 8000       | Python code Prometheus API     | http://localhost:8000  |
