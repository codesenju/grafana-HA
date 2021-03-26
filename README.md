# Grafana High Avialability

![Architecture](./images/grafana-high-availability.png)

### Breakdown:
- Nginx will serve as our Load Balancer.
- Postgres will store our data.

### Quick start:
```bash
docker compose up -d
```
\
Go to [localhost](http://localhost)