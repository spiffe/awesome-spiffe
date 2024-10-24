<p align="center">
  <img width="300" height="300" src="./.img/spiffe-icon.png">
</p>

# Awesome SPIFFE
This repository contains a curated collection of awesome software things related to the SPIFFE and SPIRE projects. It is broken down into sections, each describing a different type of awesome thing (e.g. SPIRE plugins, SPIFFE issuers, etc).

This curation is maintained by the SPIFFE project with help from the community. If you know of something awesome that is not listed here, please send a PR!

## SPIFFE Issuers
This section captures projects that are capable of issuing SPIFFE identities to workloads (but do not necessarily implement the SPIFFE Workload API to do so).

* SPIRE
* Vault
* Consul
* Istio
* Kong
* Dapr
* Athenz
* [Teleport](https://github.com/gravitational/teleport)

## SPIFFE-aware Software
This section captures projects that are capable of using SVIDs to identify themselves and their peers (i.e. they support SPIFFE authentication). If a piece of software is listed in the `SPIFFE Issuers` section, then it is implied that it is SPIFFE-aware.

* Envoy
* SPIRE
* gRPC
* [Ghostunnel](https://github.com/ghostunnel/ghostunnel) - Light-weight server or client TLS proxy with support for basic access control.
* Knox
* Keywhiz
* [Traefik](https://doc.traefik.io/traefik/https/spiffe/) - Modern open source reverse proxy and ingress controller that makes deploying services and APIs easy.

## SPIFFE Libraries

Maintained by the SPIFFE project:

* [go-spiffe](https://github.com/spiffe/go-spiffe) - SPIFFE SDK for Go
* [java-spiffe](https://github.com/spiffe/java-spiffe) - SPIFFE SDK for Java

Maintained by the community:

* [rust-spiffe](https://github.com/maxlambrecht/rust-spiffe) - SPIFFE SDK for Rust
* [py-spiffe](https://github.com/HewlettPackard/py-spiffe) - SPIFFE SDK for Python

## SPIRE Integrations
This section captures the list of software/platforms that SPIRE integrates with, either via built-in support or via discrete supporting components.

* Kubernetes
* Docker
* Envoy
* AWS
* GCP
* Azure

## 3rd Party SPIRE Plugins
This section captures community-supported SPIRE plugins.

* TPM Node Attestor

