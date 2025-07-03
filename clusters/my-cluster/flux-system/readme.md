# Flux Systemorder für Cluster

In diesem Ordner alle Objekte vorhalten zum aktuell halten des Clusters durch Flux:
- local-cluster.yaml: Aktuell halten der Applikationen auf dem Cluster 
- infrastructure.yaml: Kustomization für Infrastruktur, also zentrale komponenten die auf alle Cluster kommen, z.B. flux 
- cluster-config.yaml: ConfigMap für Clusterspezifische Einstellungen und Variablen
- git-repo-cluster.yaml: Flux-GitRepository-Ressource, welche auf das cluster-config-Repository verweist
- git-repo-secret.yaml: Credentials für das Git Repo

