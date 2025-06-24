# Environnement Grafana + Loki + Promtail

Ce projet a été écrit par **Enrick BILBA**.

Il permet de connecter Grafana à tous les conteneurs Docker d'un serveur VPS afin de centraliser, visualiser et analyser les logs de chaque application.

## Fonctionnalités principales
- **Collecte automatique des logs** de tous les conteneurs Docker via Promtail.
- **Stockage et indexation des logs** avec Loki.
- **Visualisation et filtrage avancés** grâce à Grafana (tableaux de bord, recherches par image ou nom de conteneur, etc.).
- **Déploiement automatisé** via GitHub Actions (voir `.github/workflows/main.yml`).

## Structure
- `infra/promtail.yaml` : configuration de Promtail pour la collecte des logs Docker.
- `.github/workflows/main.yml` : pipeline CI/CD pour déployer Grafana, Loki et Promtail sur un VPS.

## Auteur
Enrick BILBA
