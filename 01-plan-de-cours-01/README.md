### Titre du Cours : Introduction à Kubernetes

#### Objectifs du cours :
- Comprendre les concepts fondamentaux de Kubernetes.
- Apprendre à déployer et gérer des applications conteneurisées avec Kubernetes.
- Maîtriser les outils et techniques pour l'orchestration de conteneurs.

#### Plan du Cours :

### Chapitre 1 : Introduction à Kubernetes
1. **Leçon 1 : A l'abordage !**
2. **Leçon 2 : Introduction à la stack DevOps**
3. **Leçon 3 : Qu'est-ce que Kubernetes ?**
4. **Leçon 4 : L'architecture de Kubernetes**
5. **Leçon 5 : L'écosystème des conteneurs : Docker, Kubernetes et OCI/CRI**
6. **Leçon 6 : Explications sur l'environnement et mise en place sur Linux**
7. **Leçon 7 : Mise en place de l'environnement sur Windows**
8. **Leçon 8 : Mise en place de l'environnement sur macOS**
9. **Leçon 9 : Présentation du dashboard Minikube et de kubectl**

### Chapitre 2 : Introduction aux principaux objets Kubernetes
10. **Leçon 10 : Les objets Kubernetes**
11. **Leçon 11 : Décrire les objets Kubernetes (object spec)**
12. **Leçon 12 : Introduction aux Pods**
13. **Leçon 13 : Introduction aux déploiements (Deployments)**
14. **Leçon 14 : Introduction aux Services**

### Chapitre 3 : Les fondamentaux sur les objets Kubernetes
15. **Leçon 15 : Cycle de vie des Pods et des conteneurs**
16. **Leçon 16 : Les labels et les sélecteurs**
17. **Leçon 17 : Les ReplicaSets**
18. **Leçon 18 : Les Deployments en détail**
19. **Leçon 19 : Les Services en détail**
20. **Leçon 20 : Les Namespaces**

### Chapitre 4 : Projet 1 - Utiliser des images personnalisées avec K8s localement
21. **Leçon 21 : Introduction au projet et présentation de Docker Hub**
22. **Leçon 22 : Création du registre et push de notre image**
23. **Leçon 23 : Utilisation locale d'une image personnalisée avec K8s**
24. **Leçon 24 : Autobuild et mise à jour locale**

### Chapitre 5 : Introductions aux Ingress
25. **Leçon 25 : Qu'est-ce qu'un Ingress ?**
26. **Leçon 26 : Les composants d'un Ingress**
27. **Leçon 27 : Les règles Ingress**
28. **Leçon 28 : Utiliser un Ingress avec minikube**

### Chapitre 6 : Projet 2 - Premier cluster (DOKS)
29. **Leçon 29 : Introduction au projet**
30. **Leçon 30 : Configuration du premier cluster**
31. **Leçon 31 : Déploiement et Service NodePort**
32. **Leçon 32 : Service LoadBalancer et nom de domaine**
33. **Leçon 33 : Applications multiples avec Ingress**

### Chapitre 7 : Les sondes (Probes)
34. **Leçon 34 : Introduction aux sondes**
35. **Leçon 35 : Configurer une sonde de vitalité (liveness probe)**
36. **Leçon 36 : Configurer une sonde de démarrage (startup probe)**
37. **Leçon 37 : Configurer une sonde de préparation (readiness probe)**
38. **Leçon 38 : Utiliser d'autres sondes (TCP, exec, gRPC)**

### Chapitre 8 : Gestion des ressources
39. **Leçon 39 : Allouer et limiter les ressources utilisées par les conteneurs**
40. **Leçon 40 : Allouer et limiter la mémoire utilisée par des conteneurs**
41. **Leçon 41 : Allouer et limiter le CPU utilisé par des conteneurs**
42. **Leçon 42 : Introduction à l'autoscale**
43. **Leçon 43 : Mise à l'échelle automatique horizontale des Pods (HorizontalPodAutoscaler)**
44. **Leçon 44 : Mise à l'échelle verticale automatique (VerticalPodAutoscaler)**
45. **Leçon 45 : Mise à l'échelle automatique horizontale des Nodes (ClusterAutoscaler)**

### Chapitre 9 : Introduction à la persistance
46. **Leçon 46 : Introduction aux volumes**
47. **Leçon 47 : Utilisation d'un volume éphémère**
48. **Leçon 48 : Présentation des volumes persistants (PV) et revendication de Volume Persistant (PVC)**
49. **Leçon 49 : Exemple d'utilisation d'un PV avec PVC dans un Pod**
50. **Leçon 50 : Classe de stockage (StorageClass)**
51. **Leçon 51 : Introduction aux StatefulSets**
52. **Leçon 52 : Implémentation d'un statefulSet**

### Chapitre 10 : Projet 3 - PV, PVC et StatefulSet - NGINX/PHP/MySQL (DOKS + AKS)
53. **Leçon 53 : Cluster DOKS et volume persistant**
54. **Leçon 54 : Création d'un cluster AKS**
55. **Leçon 55 : Initialisation du projet**
56. **Leçon 56 : Création de l'image PHP-FPM**
57. **Leçon 57 : StatefulSet pour MySQL**
58. **Leçon 58 : Service headless pour MySQL**
59. **Leçon 59 : Deployment pour NGINX, PHP-FPM et initContainer**
60. **Leçon 60 : Service Load Balancer**
61. **Leçon 61 : Persistance du volume, du Load Balancer et lancement d'un dossier de configurations**
62. **Leçon 62 : Réplications pour l'application**

### Chapitre 11 : Gestion des configurations
63. **Leçon 63 : Introduction aux ConfigMaps**
64. **Leçon 64 : Utilisation des ConfigMaps dans les Pods**
65. **Leçon 65 : Introduction aux Secrets**
66. **Leçon 66 : Utilisation des Secrets**
67. **Leçon 67 : Sécurisation des Secrets**

### Chapitre 12 : Projet 4 - ConfigMap et Secret (AKS)
68. **Leçon 68 : Objectifs et configuration de NGINX avec un ConfigMap**
69. **Leçon 69 : Utilisation d'un dépôt privé**
70. **Leçon 70 : Utilisation de Secrets pour MySQL**
71. **Leçon 71 : Utilisation d'un coffre (Secrets Vault)**
72. **Leçon 72 : Configuration du vault AKS**

### Chapitre 13 : Ordonnancement avancé des Pods sur des Nodes
73. **Leçon 73 : Rappels sur l'ordonnancement des Pods (scheduling)**
74. **Leçon 74 : Affinité, anti-affinité et sélecteurs**
75. **Leçon 75 : Les teintes et les tolérances**
76. **Leçon 76 : Contraintes de diffusion des Pods**
77. **Leçon 77 : Priorité et préemption des Pods**
78. **Leçon 78 : Éviction sous pression des Nodes**

### Chapitre 14 : Logging et Monitoring avec Kubernetes
79. **Leçon 79 : Introduction au logging et monitoring**
80. **Leçon 80 : Installation de Grafana, Loki et Promtail**
81. **Leçon 81 : Prise en main de Loki**
82. **Leçon 82 : Première alerte Grafana**
83. **Leçon 83 : Installation et configuration de Prometheus**
84. **Leçon 84 : Premier graphe sur Grafana**

### Chapitre 15 : Utilisation de TLS avec Kubernetes
85. **Leçon 85 : Le protocole TLS**
86. **Leçon 86 : Certificats X.509 et HTTPS**
87. **Leçon 87 : Fonctionnement de cert-manager et installations**
88. **Leçon 88 : Configuration de cert-manager**
89. **Leçon 89 : Mise en pratique sur AKS**

### Chapitre 16 : Les tâches avec Kubernetes
90. **Leçon 90 : Les Jobs**
91. **Leçon 91 : Utilisation d'un Job**
92. **Leçon 92 : Les CronJobs**
93. **Leçon 93 : Mise en application dans le projet**

### Chapitre 17 : Introduction à Helm
94. **Leçon 94 : Introduction à Helm**
95. **Leçon 95 : Installations basiques avec Helm**
96. **Leçon 96 : Personnaliser l'installation d'un Chart**
97. **Leçon 97 : Mise à jour et retour en arrière**
98. **Leçon 98 : Désinstallation d'une release**
99. **Leçon 99 : Créer un chart avec Helm**

### Chapitre 18 : Projet 5 - Projet complet GKE
100. **Leçon 100 : Mise en place**
101. **Leçon 101 : Création des images**
102. **Leçon 102 : Déploiement et Service pour l'application Vue servie par NGINX**
103. **Leçon 103 : Installation de MongoDB**
104. **Leçon 104 : Déploiement pour l'API Node**
105. **Leçon 105 : Premier In

gress**
106. **Leçon 106 : Configuration TLS sur GKE**
107. **Leçon 107 : Monitoring**
108. **Leçon 108 : Sauvegarde et restauration MongoDB**

### Chapitre 19 : GitOps avec Argo CD (GKE)
109. **Leçon 109 : Introduction aux GitOps**
110. **Leçon 110 : Introduction à Argo CD**
111. **Leçon 111 : Installation d'Argo CD**
112. **Leçon 112 : Première application Argo CD**
113. **Leçon 113 : Séparation des répertoires de code et k8s**
114. **Leçon 114 : Description du pipeline CI/CD et synchro auto d'Argo CD**
115. **Leçon 115 : Introduction aux Github Actions**
116. **Leçon 116 : Build, tagging et mise à disposition des images sur Docker Hub**
117. **Leçon 117 : Mise à jour automatique du répertoire infra**

---

Ce plan de cours couvre une introduction complète à Kubernetes, avec des leçons détaillées et des projets pratiques pour renforcer l'apprentissage. Si vous avez des sections supplémentaires ou des modifications spécifiques à apporter, n'hésitez pas à me le faire savoir !
