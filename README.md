# Déploiement de wordpress

- Créez un deployment mysql avec un seul replicat
- Créez un service de type clusterIP pour exposer les pods mysql
- Créez un deployment wordpress avec les variables d'environnement pour se connecter à la BD mysql
- Créez un service de type nodeport pour exposer le frontend wordpress
- Infrastructure As Code

