# Catalogue des captures d’écran

Les captures ont été **renommées selon leur contenu** pour améliorer la navigation GitHub. Un tableau de correspondance avec les noms originaux est fourni plus bas. Les descriptions facilitent l’identification ; les constatations de sécurité sont détaillées dans le README.

## Nmap, Docker et inventaire local

- [01-nmap-version-kali.png](../evidence/01-nmap/01-nmap-version-kali.png) — Nmap : résultat de découverte sur scanme.nmap.org.
- [02-diagnostic-localstack-demarrage.png](../evidence/01-nmap/02-diagnostic-localstack-demarrage.png) — Nmap : étapes de reconnaissance.
- [03-localstack-redemarrage.png](../evidence/01-nmap/03-localstack-redemarrage.png) — LocalStack : démarrage/console.
- [04-localstack-etat-services.png](../evidence/01-nmap/04-localstack-etat-services.png) — LocalStack : diagnostic de santé.
- [05-nmap-scan-externe-initial.png](../evidence/01-nmap/05-nmap-scan-externe-initial.png) — Nmap : scan initial externe.
- [06-nmap-scan-versions-externe.png](../evidence/01-nmap/06-nmap-scan-versions-externe.png) — Nmap : scan des versions.
- [07-nmap-localhost-ports-courants.png](../evidence/01-nmap/07-nmap-localhost-ports-courants.png) — Nmap : localhost / ports courants.
- [08-nmap-localstack-port-4566.png](../evidence/01-nmap/08-nmap-localstack-port-4566.png) — Nmap : port 4566 LocalStack.
- [09-docker-pull-juice-shop.png](../evidence/01-nmap/09-docker-pull-juice-shop.png) — Juice Shop : récupération image Docker.
- [10-docker-run-juice-shop.png](../evidence/01-nmap/10-docker-run-juice-shop.png) — Juice Shop : lancement conteneur.
- [11-docker-conteneurs-actifs.png](../evidence/01-nmap/11-docker-conteneurs-actifs.png) — Docker : conteneurs actifs.
- [12-juice-shop-interface-web.png](../evidence/01-nmap/12-juice-shop-interface-web.png) — Juice Shop : interface navigateur.
- [13-nmap-services-locaux-3000-4566.png](../evidence/01-nmap/13-nmap-services-locaux-3000-4566.png) — Nmap : ports 3000 et 4566.
- [14-ss-ports-et-processus.png](../evidence/01-nmap/14-ss-ports-et-processus.png) — ss : ports et processus locaux.
- [15-ps-docker-proxy-localstack.png](../evidence/01-nmap/15-ps-docker-proxy-localstack.png) — ps : processus docker-proxy port 4566.
- [16-ps-docker-proxy-juice-shop.png](../evidence/01-nmap/16-ps-docker-proxy-juice-shop.png) — ps : processus docker-proxy port 3000.
- [17-ps-processus-containerd.png](../evidence/01-nmap/17-ps-processus-containerd.png) — ps : processus containerd.

## Audit web ZAP

- [01-zap-execution-scan-baseline.png](../evidence/02-zap/01-zap-execution-scan-baseline.png) — ZAP : exécution du baseline scan.
- [02-zap-synthese-rapport.png](../evidence/02-zap/02-zap-synthese-rapport.png) — ZAP : synthèse du rapport HTML.
- [03-zap-statistiques-exploration.png](../evidence/02-zap/03-zap-statistiques-exploration.png) — ZAP : insights de scans.
- [04-zap-liste-alertes.png](../evidence/02-zap/04-zap-liste-alertes.png) — ZAP : catégories d’alertes.
- [05-prowler-commande-non-disponible.png](../evidence/02-zap/05-prowler-commande-non-disponible.png) — Prowler : tentative avant installation.

## Posture Cloud Prowler

- [01-prowler-installation-venv.png](../evidence/03-prowler/01-prowler-installation-venv.png) — Prowler : installation dans un environnement Python.
- [02-prowler-version-5-45.png](../evidence/03-prowler/02-prowler-version-5-45.png) — Prowler : version installée.
- [03-docker-conteneurs-arretes.png](../evidence/03-prowler/03-docker-conteneurs-arretes.png) — Docker : aucun conteneur actif à ce moment.
- [04-configuration-endpoints-aws.png](../evidence/03-prowler/04-configuration-endpoints-aws.png) — AWS CLI : configuration d’endpoint local.
- [05-validation-endpoints-boto3.png](../evidence/03-prowler/05-validation-endpoints-boto3.png) — Boto3 : confirmation endpoints STS S3 IAM.
- [06-prowler-lancement-audit.png](../evidence/03-prowler/06-prowler-lancement-audit.png) — Prowler : commande initiale.
- [07-prowler-resultats-avant.png](../evidence/03-prowler/07-prowler-resultats-avant.png) — Prowler : audit initial résumé.
- [08-prowler-fichiers-rapports.png](../evidence/03-prowler/08-prowler-fichiers-rapports.png) — Prowler : génération fichiers CSV et HTML.
- [09-prowler-detail-fail-avant.png](../evidence/03-prowler/09-prowler-detail-fail-avant.png) — Prowler : HTML initial et checks en échec.
- [10-iam-absence-password-policy.png](../evidence/03-prowler/10-iam-absence-password-policy.png) — IAM : absence de politique explicite.
- [11-iam-correction-password-policy.png](../evidence/03-prowler/11-iam-correction-password-policy.png) — IAM : paramétrage de politique de mots de passe.
- [12-iam-politique-verifiee.png](../evidence/03-prowler/12-iam-politique-verifiee.png) — IAM : vérification de la politique appliquée.
- [13-prowler-resultats-apres.png](../evidence/03-prowler/13-prowler-resultats-apres.png) — Prowler : audit après remédiation.


## Correspondance avec les noms d’origine

| Nom d’origine | Nom GitHub |
|---|---|
| `Screenshot 2026-10-18 231503.png` | [`01-nmap-version-kali.png`](../evidence/01-nmap/01-nmap-version-kali.png) |
| `Screenshot 2026-10-18 231545.png` | [`02-diagnostic-localstack-demarrage.png`](../evidence/01-nmap/02-diagnostic-localstack-demarrage.png) |
| `Screenshot 2026-10-18 231633.png` | [`03-localstack-redemarrage.png`](../evidence/01-nmap/03-localstack-redemarrage.png) |
| `Screenshot 2026-10-18 231658.png` | [`04-localstack-etat-services.png`](../evidence/01-nmap/04-localstack-etat-services.png) |
| `Screenshot 2026-10-18 232120.png` | [`05-nmap-scan-externe-initial.png`](../evidence/01-nmap/05-nmap-scan-externe-initial.png) |
| `Screenshot 2026-10-18 232639.png` | [`06-nmap-scan-versions-externe.png`](../evidence/01-nmap/06-nmap-scan-versions-externe.png) |
| `Screenshot 2026-10-18 232700.png` | [`07-nmap-localhost-ports-courants.png`](../evidence/01-nmap/07-nmap-localhost-ports-courants.png) |
| `Screenshot 2026-10-18 232804.png` | [`08-nmap-localstack-port-4566.png`](../evidence/01-nmap/08-nmap-localstack-port-4566.png) |
| `Screenshot 2026-10-18 232959.png` | [`09-docker-pull-juice-shop.png`](../evidence/01-nmap/09-docker-pull-juice-shop.png) |
| `Screenshot 2026-10-18 233022.png` | [`10-docker-run-juice-shop.png`](../evidence/01-nmap/10-docker-run-juice-shop.png) |
| `Screenshot 2026-10-18 233043.png` | [`11-docker-conteneurs-actifs.png`](../evidence/01-nmap/11-docker-conteneurs-actifs.png) |
| `Screenshot 2026-10-18 233141.png` | [`12-juice-shop-interface-web.png`](../evidence/01-nmap/12-juice-shop-interface-web.png) |
| `Screenshot 2026-10-18 233347.png` | [`13-nmap-services-locaux-3000-4566.png`](../evidence/01-nmap/13-nmap-services-locaux-3000-4566.png) |
| `Screenshot 2026-10-18 233419.png` | [`14-ss-ports-et-processus.png`](../evidence/01-nmap/14-ss-ports-et-processus.png) |
| `Screenshot 2026-10-18 233500.png` | [`15-ps-docker-proxy-localstack.png`](../evidence/01-nmap/15-ps-docker-proxy-localstack.png) |
| `Screenshot 2026-10-18 233521.png` | [`16-ps-docker-proxy-juice-shop.png`](../evidence/01-nmap/16-ps-docker-proxy-juice-shop.png) |
| `Screenshot 2026-10-18 233542.png` | [`17-ps-processus-containerd.png`](../evidence/01-nmap/17-ps-processus-containerd.png) |
| `Screenshot 2026-10-18 234846.png` | [`01-zap-execution-scan-baseline.png`](../evidence/02-zap/01-zap-execution-scan-baseline.png) |
| `Screenshot 2026-10-18 234926.png` | [`02-zap-synthese-rapport.png`](../evidence/02-zap/02-zap-synthese-rapport.png) |
| `Screenshot 2026-10-18 234939.png` | [`03-zap-statistiques-exploration.png`](../evidence/02-zap/03-zap-statistiques-exploration.png) |
| `Screenshot 2026-10-18 234952.png` | [`04-zap-liste-alertes.png`](../evidence/02-zap/04-zap-liste-alertes.png) |
| `Screenshot 2026-10-18 235827.png` | [`05-prowler-commande-non-disponible.png`](../evidence/02-zap/05-prowler-commande-non-disponible.png) |
| `Screenshot 2026-10-19 000038.png` | [`01-prowler-installation-venv.png`](../evidence/03-prowler/01-prowler-installation-venv.png) |
| `Screenshot 2026-10-19 001148.png` | [`02-prowler-version-5-45.png`](../evidence/03-prowler/02-prowler-version-5-45.png) |
| `Screenshot 2026-10-19 001214.png` | [`03-docker-conteneurs-arretes.png`](../evidence/03-prowler/03-docker-conteneurs-arretes.png) |
| `Screenshot 2026-10-19 001525.png` | [`04-configuration-endpoints-aws.png`](../evidence/03-prowler/04-configuration-endpoints-aws.png) |
| `Screenshot 2026-10-19 001546.png` | [`05-validation-endpoints-boto3.png`](../evidence/03-prowler/05-validation-endpoints-boto3.png) |
| `Screenshot 2026-10-19 001620.png` | [`06-prowler-lancement-audit.png`](../evidence/03-prowler/06-prowler-lancement-audit.png) |
| `Screenshot 2026-10-19 001942.png` | [`07-prowler-resultats-avant.png`](../evidence/03-prowler/07-prowler-resultats-avant.png) |
| `Screenshot 2026-10-19 002003.png` | [`08-prowler-fichiers-rapports.png`](../evidence/03-prowler/08-prowler-fichiers-rapports.png) |
| `Screenshot 2026-10-19 002100.png` | [`09-prowler-detail-fail-avant.png`](../evidence/03-prowler/09-prowler-detail-fail-avant.png) |
| `Screenshot 2026-10-19 002229.png` | [`10-iam-absence-password-policy.png`](../evidence/03-prowler/10-iam-absence-password-policy.png) |
| `Screenshot 2026-10-19 002333.png` | [`11-iam-correction-password-policy.png`](../evidence/03-prowler/11-iam-correction-password-policy.png) |
| `Screenshot 2026-10-19 002353.png` | [`12-iam-politique-verifiee.png`](../evidence/03-prowler/12-iam-politique-verifiee.png) |
| `Screenshot 2026-10-19 002459.png` | [`13-prowler-resultats-apres.png`](../evidence/03-prowler/13-prowler-resultats-apres.png) |
