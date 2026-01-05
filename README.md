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
## Day 9
- Image optimization
- Multi-stage builds
- .dockerignore
- Docker security basics
# Docker DevOps Lab

## Overview
Hands-on Docker training covering image building, optimization,
multi-container applications, and production-like configuration.

## Topics
- Dockerfile & images
- docker-compose
- Networking & volumes
- Environment variables
- Healthchecks & restart policies
- Security & optimization
## Day 11
- CI/CD fundamentals
- GitHub Actions basics
- First automated pipeline
## Day 12
- CI build and test
- Python dependencies
- Automated test execution
- Pipeline failure handling
## Day 13
- Docker image build in CI
- Image tagging with commit SHA
- CI validation of Dockerfile
- Day 14: Push to GHCR
