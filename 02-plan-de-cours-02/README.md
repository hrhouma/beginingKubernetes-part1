### Objectifs Pédagogiques
À l’issue de la formation, le participant sera en mesure de :
- Comprendre le positionnement de Kubernetes et la notion d'orchestration.
- Installer Kubernetes et ses différents composants.
- Utiliser les fichiers descriptifs YAML.
- Définir les bonnes pratiques pour travailler avec Kubernetes.

### Public Concerné
Développeurs, architectes, ingénieurs de production, administrateurs.

### Prérequis
- Administration système Linux.
- Connaissances générales en conteneurisation (Docker ou CoreOS).

### Programme de la Formation

#### Jour 1 : Introduction à Kubernetes et Installation

**Introduction à Kubernetes**
- De la virtualisation à la conteneurisation.
- Le couple Docker/Kubernetes.
- Solutions d'installation (MiniKube, On-Premise, etc.).

**Installation et Configuration**
- Installation et configuration de Docker.
- Accéder au cluster Kubernetes : CLI (kubectl), GUI (dashboard) et APIs.
- Déploiement et publication manuelle.
- Détail et introspection du déploiement.

**Travaux Pratiques**
- Déploiement d'une plateforme de test.

#### Jour 2 : Fichiers Descriptifs et Architecture Kubernetes

**Les Fichiers Descriptifs**
- Syntaxe YAML.
- Scalabilité d'un déploiement.
- Stratégie de mise à jour sans interruption (update/rollback).
- Suppression d'un déploiement.

**Travaux Pratiques**
- Déploiement, publication et analyse d'un déploiement.

**Architecture Kubernetes**
- Composants du master node : API server, scheduler, controller manager, etc.
- Architecture d'un nœud : Kubelet, le moteur de conteneur (docker), Kube-proxy.
- Objets Kubernetes : volume, service, pod, etc.
- Objet statefull, objet stateless.
- Solution du deployment.

**Travaux Pratiques**
- Utilisation de deployment.

#### Jour 3 : Exploitation et Production avec Kubernetes

**Exploiter Kubernetes**
- Clusterisation avec replicas et deployment.
- Types de services.
- Labels et choix d'un nœud pour le déploiement.
- Affinité et anti-affinité.
- Daemons set, health check, config map et secrets.
- Persistent Volumes et Persistent Volumes Claim.

**Travaux Pratiques**
- Déploiement d'une base de données et d'une application.

**Kubernetes en Production**
- Frontal administrable Ingress.
- Limitation de ressources.
- Gestion des ressources et autoscaling.
- Service Discovery (env, DNS).
- Les namespaces et les quotas.
- Gestion des accès.
- Haute disponibilité et mode maintenance.

**Travaux Pratiques**
- Déploiement de conteneur et gestion de la montée en charge.

#### Jour 4 : Déploiement d'un Cluster Kubernetes

**Déploiement d'un Cluster Kubernetes**
- Préparation des nœuds.
- Déploiement : d'un master-nodeadm, d'un master-node, d'un worker-node.
- Mise en place du Dashboard et du réseau.

**Travaux Pratiques**
- Déploiement d'un cluster.

### Modalités d'Évaluation
- Évaluation continue à travers des QCM, mises en situation et travaux pratiques.
- Test de positionnement en amont et en aval pour valider les compétences acquises.
