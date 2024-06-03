# Camunda-Workflow-Engine
Personal Camunda Workflow Engine from Camunda

## INstallation
### First run
```bash
docker pull camunda/camunda-bpm-platform:run-latest
docker run -d --name camunda -p 8080:8080 camunda/camunda-bpm-platform:run-latest
```

### Runs thereafter
```bash
docker start camunda
OR
docker run -d -p 8080:8080 camunda/camunda-bpm-platform:run-latest
```

### Login
Username: demo
Password: demo

### Stop the container
```bash
docker stop camunda
```

## How to run the project
- https://docs.camunda.org/manual/7.21/installation/docker/