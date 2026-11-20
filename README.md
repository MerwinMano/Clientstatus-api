# Client Status Portal — API

Backend for the Client Status Portal: REST API, review workflow (Developer → Technical Lead →
Delivery Manager → Client), and the sync service that reads Jira, GitHub and SharePoint.
The web front end lives in [Clientstatus](https://github.com/MerwinMano/Clientstatus).

- API base URL: https://clientstatus.agripal.com/api
- Stack: Spring Boot 3 (Java 21), PostgreSQL 16 (Flyway), Keycloak (OAuth2 resource server)

## Branches

| Branch | Purpose |
| --- | --- |
| `main` | Released code; deploys to production |
| `dev`  | Ongoing work; deploys to staging (clientstatus-staging.agripal.com) |
