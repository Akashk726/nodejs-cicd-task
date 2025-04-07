# Node.js CI/CD Task
A sample Node.js app with a CI/CD pipeline using GitHub Actions and Docker.

## How It Works
- On push to `main`, the pipeline:
  1. Checks out code.
  2. Installs Node.js and dependencies.
  3. Runs tests (if any).
  4. Builds and pushes a Docker image to DockerHub.

## Files
- `index.js`: Node.js app code.
- `Dockerfile`: Docker configuration.
- `.github/workflows/main.yml`: CI/CD pipeline.
- `screenshot.png`: Workflow success screenshot (optional).

## DockerHub
Image: `akash5507/nodejs-demo-app:latest`
