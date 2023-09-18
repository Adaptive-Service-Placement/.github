  ## ADAPTIVE SERVICE PLACEMENT

  Within this Bachelor Thesis, we propose a framework that extends a running application and adapts the microservice placement in a Kubernetes Cluster at runtime based on extracted messaging information. The goal is to minimize network communication overhead and message latency between frequently communicating microservices. We aim to achieve a reduction of the network communication overhead by placing respective services onto the same Kubernetes Node, which results in having the microservices exchange most of the messages while being hosted on the same physical machine.

## Architecture

![new_saga_overview](https://github.com/Adaptive-Service-Placement/.github/assets/94569533/e7972120-25a1-43db-a5b6-cfaa74ae4fee)
