```mermaid
graph TD;
docker --> gitea --> drone;
docker(install Docker);
gitea(create gitea container);
drone(create Drone container);
```
