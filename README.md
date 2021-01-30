# Voting App Example

Example distributed solution for learning and testing twelve factor, distributed, and cloud native concepts. This is an extended version of the [Docker example voting app repo](https://github.com/dockersamples/example-voting-app).

## Steps to get started

1. Clone this repo
    - Create a directory and clone the repos inside it
    - an `ls` should look like this

      ```shell
      .
      ..
      example-voting
      example-voting-result
      example-voting-vote
      example-voting-worker
      example-voting-misc
      ```

2. Install Docker
    - macOS: Docker Desktop for macOS
    - Windows: Docker Desktop for Windows (supports WSL2 or Hyper-V mode)
    - Linux: Docker Engine and Docker Compose

3. Run it in Docker Compose (`cd` to this repo root)
    - Bring up whole solution by building images from local source code
      - `docker-compose up`
    - Bring up whole solution using Harbor images (without needing source code cloned)
      - `docker-compose -f docker-compose.images.yml up`

## Coming soon

1. Install Kubernetes
    - macOS: Enable it in Docker Desktop preferences
    - Windows: Enable it in Docker Desktop preferences
    - Linux: Install MicroK8s

2. Deploy to Kubernetes
    - `kubectl apply -f ....`
