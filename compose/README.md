# Docker Compose Configuration

This directory is reserved for Docker Compose configuration used to run the Portfolio Platform components together.

## Ownership

The platform repository will coordinate:

- Portfolio Web
- Portfolio API
- Portfolio Worker
- PostgreSQL

Component-specific application code, dependency declarations, tests, and Dockerfiles remain in their respective repositories.

## Current Status

Docker Compose orchestration has not yet been implemented.

Future orchestration configuration will be introduced under PORT-17 after the relevant component containerization and PostgreSQL setup work.

No Docker services or environment variables are required by this directory at present.
