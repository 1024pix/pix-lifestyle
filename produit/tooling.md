# Outillage technique

## Communication

Pour facilier la communication, nous utilisons plusieurs outils :
- Jira pour le suivi de projet
- Slack pour la communication écrite quotidienne
- Google Meet pour la communication orale en ligne
- GitHub pour historiser les sources de nos projets
- Circle CI pour exécuter nos tests automatisés
- Gmail pour les mails

## Developer eXperience

Pour l'expérience la plus confortable, nous avons des outils pour nous assister :
- Des [Review Apps (RA)](https://doc.scalingo.com/platform/app/review-apps) pour tester fonctionnellement nos applications depuis les Pull Requests (PRs)
- [Un bot pour faire les mises en recette et mises en production depuis un canal Slack dédié](https://github.com/1024pix/pix-bot), ce sont les Product Owners (PO) qui s'en chargent
- Une GitHub Action [:rocket: Ready to merge](https://github.com/1024pix/pix-actions#auto-merge) pour rebase et merger automatiquement nos PRs après approbation (et ainsi déployer sur l'environnement d'intégration)
- [Un script pour ajouter les liens des RA directement dans nos PR](https://github.com/1024pix/pix/blob/dev/scripts/signal_deploy_to_pr.sh)
- Des scripts pour déplacer automatiquement les tickets Jira :
  * [De ToDo à Doing](https://github.com/1024pix/pix/blob/dev/.github/workflows/jira-transition-to-dev-in-progress.yaml) lorsqu'une PR est ouverte
  * [De Doing à Review](https://github.com/1024pix/pix/blob/dev/.github/workflows/jira-transition-to-review.yaml) lorsqu'une PR est prête à être review
  * [De Review à Intégration](https://github.com/1024pix/pix/blob/dev/.github/workflows/on-dev-merge.yaml) lorsque la PR est mergée
- [Un script pour ajouter les liens de la PR et des RA dans les tickets Jira](https://github.com/1024pix/pix/blob/dev/scripts/jira/comment-with-review-app-url.js)
- Des connexions Slack diverses 
