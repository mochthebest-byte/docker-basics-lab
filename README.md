# Docker Basics Lab

Day 1 of DevOps roadmap.

Topics:
- Docker architecture
- Images vs containers
- Basic docker commands
## Day 2 – Docker CLI & Container Lifecycle

### Practiced commands
- docker run (detached mode)
- docker ps / ps -a
- docker stop / start / rm
- docker logs / logs -f
- docker exec
- port mapping (8080:80)

### Labs
- Ran nginx containers (web, web2)
- Verified access via browser
- Alpine container with sleep + ps
- Understood container name conflicts

## Day 3
- Dockerfile anatomy
- Image layers
- CMD vs ENTRYPOINT
- Custom image build
## Day 4
- Stateless containers
- Docker volumes
- Bind mounts
- Persistent data (Postgres, Zabbix case)
## Day 5
- Docker bridge networks
- Container-to-container communication
- DNS service discovery
- Zabbix app-db networking
## Day 6
- docker-compose basics
- Multi-container application
- Service dependencies
- Persistent volumes
## Day 7
- Environment variables
- .env configuration
- Secret handling basics
- Git security best practices
## Day 8
- Restart policies
- Healthchecks
- Service dependency conditions
- Production-like behavior
