# Docker Basics

## Common Commands
```bash
docker pull nginx
docker run -d -p 80:80 nginx
docker ps
docker stop <container_id>
docker rm <container_id>
```

## Docker Compose
```yaml
version: '3'
services:
  web:
    image: nginx
    ports:
      - "80:80"
```
