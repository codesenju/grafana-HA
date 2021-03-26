# Grafana High Avialability

![Architecture](./images/grafana-high-availability.png)
\
image source: grafana
### Breakdown:
- Nginx will serve as our Load Balancer.
- PostgreSQL 12 will store our data.

### Quick start:
```bash
docker compose up -d
```
\
Go to [localhost:8080](http://localhost:8080) on your browser.
\
\
Initial grafana sign in details:
|Username|Password|
|--------|:------:|
|admin   | admin  | 
