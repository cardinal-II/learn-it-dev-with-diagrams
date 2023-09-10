```mermaid
graph TD;
laptop-->linux-->docker --> gitea --> drone;
linux-->m_local_repo-->push
docker(install Docker);
gitea(create gitea container);
drone(create Drone container);
```
