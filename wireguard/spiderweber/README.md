# spiderweb

nest = docs

- TODO: Make it use hugo and have a Web Server host it, so it can be docker deployed.

---

wasp = admin cli

- uses GRPC, so we can then make a GUI Management API using Flutter
- In order to support Flutter Web, we probably have to start to use the GRPC gateway.
  - see: https://medium.com/swlh/rest-over-grpc-with-grpc-gateway-for-go-9584bfcbb835

---


mosquito = wireguard client ( desktop)

- Make a Flutter GUI

---

knot = wireguard server

- TODO: currently needs wireguard server to be present. SO run in docker, so adapt make file to use docker and expose ports, etc

---

spider = wiregiard server ops.

- connects to ETCD to get the "knots - wg-servers"


# 

* Not ordered yet.

- Convert all bash scripts to use mage to make it solid cross platform.
  - Its not many scripts.

- A docker compose to we can all run the bits locally.
  - Can also just use KO, since its all golang and we get free Kubernetes.
    - See: https://github.com/google/ko

- GRPC AND Protobug code gen in KNOTS repo.



