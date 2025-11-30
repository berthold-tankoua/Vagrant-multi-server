# 🚀 Déploiement Multi-Serveur avec Vagrant — Application Java

Ce projet permet de déployer automatiquement une application **Java (Spring Boot, Maven, JDK etc.)**
sur une infrastructure virtuelle composée de **plusieurs serveurs via Vagrant + VirtualBox**.

L'objectif est de proposer un environnement reproductible facilement, idéal pour la mise en production,
les tests ou l’intégration continue.

---

### 🔥 Machines virtuelles configurées

| Server | Rôle | Stack |
|--------|------|-------|
| **app-server** | Exécution & build de l’app Java | OpenJDK / Maven / API |
| **db-server**  | Base de données | MySQL/PostgreSQL |
| **proxy-server** | Reverse proxy HTTP | Nginx / Load Balancing |

---

## 🛠️ Technologies utilisées

| Outil | Usage |
|-------|--------|
| **Vagrant** | Provisionnement et gestion des machines virtuelles |
| **VirtualBox** | Hyperviseur pour l'exécution des VMs |
| **Java 17+** | Application backend |
| **Maven/Gradle** | Build & gestion des dépendances |
| **Nginx** | Proxy + routing vers application |
| **MySQL/PostgreSQL** | Stockage des données |

---


