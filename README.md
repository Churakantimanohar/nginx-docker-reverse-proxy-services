# nginx-docker-reverse-proxy-services
# Multi-Service App with Nginx Reverse Proxy

## Services
- **service_1**: Go backend
- **service_2**: Python backend
- **nginx**: Reverse proxy to route `/service1` and `/service2`

## How to run

```bash
docker-compose up --build
