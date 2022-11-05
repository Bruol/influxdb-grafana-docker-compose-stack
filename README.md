## A docker-compose file for grafana working together with influxdb

This is a simple docker-compose file to deploy an grafana and influxdb instance.

---

Replace **"INFLUXDB_ADMIN_USER"** and **"INFLUXDB_ADMIN_PASSWORD"** in docker-compose.yml with your username and password or use secrets and run:

```bash
docker-compose up
```