```mermaid
graph TD;
laptop-->linux-->docker;
subgraph maintainer
    docker --> gitea -->setup_gitea --> drone;
    end
linux-->m_local_repo-->push
setup_gitea-->push --> drone


docker(install Docker);
gitea(create gitea container);
drone(create Drone container);
setup_gitea("run the gitea container
  and set up gitea");
m_local_repo("the maintainer
  creates a local repo");
maintainer(the maintainer's operations on his laptop);
```
