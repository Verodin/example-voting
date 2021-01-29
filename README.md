# example-voting
Example distributed solution for learning and testing twelve factor, distributed, and cloud native concepts. This is an extended version of the [Docker example voting app repo](https://github.com/dockersamples/example-voting-app).

## Steps to get started

1. Clone repos
  - Create a directory and clone the repos inside it
2. Install Docker
  - macOS: Docker Desktop for macOS
  - Windows: Docker Desktop for Windows (supports WSL2 or Hyper-V mode)
  - Linux: Docker Engine and Docker Compose
3. (optional) Install Kubernetes
  - macOS: Enable it in Docker Desktop preferences
  - Windows: Enable it in Docker Desktop preferences
  - Linux: Install MicroK8s
3. Run it
  - Bring up whole solution using images
    - (in this repos directory) `docker-compose -f docker-compose.images.yml up`
  - Bring up whole solution by building images from source code
    - (in this repos directory) `docker-compose up`

Much more to come!
