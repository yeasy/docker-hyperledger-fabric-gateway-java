# https://github.com/yeasy/docker-hyperledger-fabric-gateway-java
#
# Dockerfile for Hyperledger fabric gateway java image.
# If you only need quickly deploy a fabric network, please see
# * yeasy/hyperledger-fabric-peer
# * yeasy/hyperledger-fabric-orderer
# * yeasy/hyperledger-fabric-ca

FROM maven:3.8-jdk-11
LABEL maintainer="yeasy@github"

RUN apt-get update \
        && apt-get install -y vim

RUN cd /opt \
        && git clone --single-branch -b release-1.4 --depth 1 https://github.com/hyperledger/fabric-gateway-java.git \
        && cd fabric-gateway-java \
        && mvn -Dmaven.test.skip=true install

WORKDIR /opt/fabric-gateway-java
