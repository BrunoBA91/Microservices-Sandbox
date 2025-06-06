# Online Lobby & Matchmaking Service - Online Game Service

I am currently working on a full-featured backend system for online multiplayer games, designed to simulate real-world production environments used by game studios.

​
The system consists of two core microservices built in C#/.NET:

- Authentication Service: Handles player registration and login using secure authentication (JWT-based maybe?)

- Matchmaking Service: Accepts player matchmaking requests, manages queues, and pairs players into matches.


All data is persisted using MongoDB, which stores player profiles, sessions, and match data. Each service is containerized using Docker to ensure cross-platform compatibility and rapid deployment. Infrastructure is provisioned via Terraform, and the entire architecture is deployed to a Kubernetes cluster for automatic scaling, load balancing, and fault tolerance.
