Hyperledger Fabric gateway in Java
===
Docker images for [Hyperledger Fabric gateway Java](https://github.com/hyperledger/fabric-gateway-java) image.

If you want to quickly deploy a local cluster without any configuration and vagrant, please refer to [Start hyperledger cluster using compose](https://github.com/yeasy/docker-compose-files#hyperledger_fabric).

# Supported tags and respective Dockerfile links

* [`latest` (latest/Dockerfile)](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/blob/master/Dockerfile): Default to track latest master branch.
* [`release-2.2` (release-2.2/Dockerfile)](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/blob/master/release-2.2/Dockerfile): 2.2.x release.
* [`release-1.4` (release-1.4/Dockerfile)](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/blob/master/release-1.4/Dockerfile): 1.4.x release.

For more information about this image and its history, please see the relevant manifest file in the [`yeasy/docker-hyperledger-fabric-gateway-java` GitHub repo](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java).

# What is hyperledger-fabric-gateway-java?
Docker image with hyperledger fabric java gateway, which will be utilized as the client to interact with the network.

# How to use this image?
The docker image is auto built at [docker hub](https://hub.docker.com/repository/docker/yeasy/hyperledger-fabric-gateway-java).

## In Dockerfile
```sh
FROM yeasy/hyperledger-fabric-gateway-java:latest
```

# Which image is based on?
The image is built based on [java](https://hub.docker.com/_/java) 12 image.

# What has been changed?
## clone fabric gateway java code
Clone the fabric gateway java code from repo.

## install dependencies
Install required `git`, `g++`, `make`, `python`, and gateway dependencies.

# Supported Docker versions

This image is officially supported on Docker version 1.12.0+.

Support for older versions (down to 1.0) is provided on a best-effort basis.

# Known Issues
* N/A.

# User Feedback
## Documentation
Be sure to familiarize yourself with the [repository's `README.md`](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/blob/master/README.md) file before attempting a pull request.

## Issues
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/issues).

You can also reach many of the official image maintainers via the email.

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/yeasy/docker-hyperledger-fabric-gateway-java/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
