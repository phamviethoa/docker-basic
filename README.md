What is Docker?

- Virtualization software? What is Virtualization?
- Packages application with all the necessary dependencies, configuration, system tools and runtime.
- Portable artifact, easily shared and distributed.

A standardized unit, that has everthing the application needs to run.

Why is Docker?

- Standardizes process of running any service on any local dev environment.
- Easy to run different versions of same app without any conflicts.
- Streamline the deployment process with Docker artifact which is include everything the app needs.

Docker vs VM?

- Docker virtualize the Application layer while VM virtualize both Kernel and Application layers.
- Docker images are much smaller than VM images.
- Docker images are faster to start than VM images.
- Docker only compatible with Linux distros while VM is compatible with all OS. 

What is Docker Image?

A Docker image is a file that contains everything needed to run a program, like code, tools, and settings.

What is Docker Container?

A Docker container is a running copy of a Docker image. It’s a lightweight, isolated environment where your application runs.

What is Docker Registry?

A Docker registry is a place where Docker images are stored and shared.

What is Docker Repository?

A Docker repository is a collection of related Docker images with the same name but different versions (tags).

What is Docker image tag?

A Docker image tag is a label used to identify a specific version of a Docker image in a repository.

What is Container Port Binding?

- Application inside container runs in an isolated Docker network
- Port Binding helps us bind the container's port to the host's port to make the service available to the outside world.

How to create your own Docker Image?

Dockerfile -build-> Image -run-> Container

Dockerfile structure
- FROM: declare the base image
- COPY: copies files or directories from <src> and adds them to the filesystem of the container at the path <dest>. COPY is executed on the host
- WORKDIR: sets the working directory for all following commands
- RUN: execute any command in a shell inside the container environment
- CMD: the instruction that is to be executed when a Docker container starts. There can only be one CMD instruction in a Dockerfile 

What is Docker Network?

- A Docker network is a way for Docker containers to communicate with each other and with the outside world. It provides isolated and secure communication between containers.
- Containers run within the same Docker network can communicate with each other using container name

What is Docker Compose?

- Docker Compose is a tool that lets you define and run multi-container Docker applications using a simple YAML file.
- Docker Compose takes care of creating a common Network

What is Docker Volumes?

- A Docker volume is a storage location used to persist data generated or used by Docker containers. It allows data to stay available even if the container is stopped or removed.
- There are 3 types of Volume: Host Volumes, Anonymous Volumes, and *Named Volumes
