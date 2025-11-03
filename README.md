# RNCP DevOps System Administrator 
# Evaluation en cours de Formation ECF3

#  🛡️ SECURISER L'INFRASTRUCTURE

## 📋 Cahier des charges :

### ✅ Partie 1 : Gestion des variables
- Créer une repo GIT
- Créer une branche DEV
- Pushez chaques prochaines étapes sur DEV
- Créer une organisation et un workspace TERRAFORM Cloud
- Connecter ce workspace au repo précédemment mentionnée Terraform Cloud
- Choisir un provider parmi cette liste : https://registry.terraform.io/browse/providers
- Créer un compte sur le provider cloud AWS : https://aws.amazon.com/
- Créer un module contenant une VM linux simple configuré à ce provider
- À la place de passer les clés API directement, passez les via des default variables dans un fichier nommé variables.tf
- Enlever ces variables de votre code et passer les via Terraform Cloud

### ✅ Partie 2 : Passage de secret à la volée
- Mettre en place un serveur VAULT avec l’option UI configurée
- Connecter le module Terraform au serveur Vault
- Faire en sorte que les clés API soient renseignées par vault et non pas vous ou vos variables terraform
- Faire une pull request sur master

### 📋 Consignes :
Pensez à commenter/versionner les scripts et à joindre des captures d’écran

### 🎯 Livrables :
- Le repo GIT
- Une organisation et un workspace TERRAFORM connectée à ce repo git
- Le serveur VAULT
