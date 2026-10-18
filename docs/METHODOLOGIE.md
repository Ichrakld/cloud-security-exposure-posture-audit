# Méthodologie et interprétation

1. **Inventaire** : identifier les hôtes et ports par Nmap, puis corréler avec `ss`, `ps` et Docker.
2. **Analyse applicative** : scanner uniquement Juice Shop en baseline passif avec ZAP ; analyser les réponses HTTP et les alertes.
3. **Posture Cloud** : auditer IAM et solliciter S3 sur LocalStack au moyen de Prowler avec de faux identifiants.
4. **Remédiation** : appliquer uniquement une politique IAM dans LocalStack, valider par AWS CLI et répéter l'audit IAM.
5. **Validation** : séparer observation, risque potentiel, recommandations et limites.

## Sécurité et autorisation

- Aucun scan actif contre des systèmes non autorisés.
- Socket Docker monté dans LocalStack : accès privilégié, réservé au labo.
- Ne jamais publier de secrets ni exporter de comptes AWS réels dans les variables d'environnement du TP.
- Éviter d'interpréter les politiques de contrôle Prowler comme une certification de conformité générale.
