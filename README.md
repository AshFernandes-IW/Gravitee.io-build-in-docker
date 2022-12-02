# Gravitee.io-build-in-docker

## Installation Instructions

- This tutorial assumes you have the latest version of [Docker](https://docs.docker.com/get-docker/) installed for your system.
- Clone the repository from GitHub
- Open a terminal in the repository directory and type `docker-compose up`
- The docker container with Gravitee.io installed should now be running

## Testing Instructions - Wiki Turtle example 🐢

- Enter `localhost:8084` in your web browser to access the Gravitee Management dashboard
- Navigate to APIs in the laft-hand navigation panel
- Click ``+Add Api`` and ``continue in the wizard``
- We will give our API a name, version, description, and context-path of ``turtle``, ``1.0``, ``turtle info``, and ``/turtle`` respectively
- Our backend will be `https://en.wikipedia.org/wiki/Turtle`
- In the Plan stage, feel free to give any name and description of your liking, but ensure the Security Type is marked as ``Keyless (public)``
- Now we will start and publish our API in the following section
- Our API is now live and we can confirm this by opening a new browser tab `localhost:8082/turtle` in the address field
