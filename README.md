# EventViewer_quest

La vue personnalisée a été crée pour surveiller spécifiquement les événements liés au service DNS et son état.

Configuration de la vue personnalisée :
Nom : Service DNS

**Niveaux surveillés :**

- Critique
- Erreur
- Avertissement
- Information - Pour les démarrages/arrêts

**Sources d'événements inclus**

- DNS-Server-Service: Pour les opérations du serveur DNS
- DNS Client Events: Pour les événements côté client

**Événements critiques (ID et leur rôle)**

- 2: Démarrage du serveur DNS
- 4: Arrêt du serveur DNS
- 409: Erreur de résolution de nom
- 501-502: Échec de chargement de zone
- 6001-6002: Problèmes de réplication DNS
