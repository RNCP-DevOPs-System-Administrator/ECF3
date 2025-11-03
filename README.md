** RNCP DevOps System Administrator **
# 🚀 EVALUATION EN COURS DE FORMATION ECF3 - ** SECURISER L'INFRASTRUCTURE **

## 📋 Cahier des charges :

### ✅ Partie 1 : Gestion des variables
- Créer une repo git
- Créer une branche dev
- Pushez chaques prochaines étapes sur dev
- Créer une organisation et un workspace Terraform Cloud
- Connecter ce workspace au repo précédemment mentionnée Terraform Cloud
- Choisir un provider parmi cette liste : https://registry.terraform.io/browse/providers
- Créer un compte sur le provider cloud AWS : https://aws.amazon.com/
- Créer un module contenant une vm linux simple configuré à ce provider
- À la place de passer les clés api directement, passez les via des default variables dans un fichier nommé variables.tf
- Enlever ces variables de votre code et passer les via Terraform Cloud

### ✅ Partie 2 : Passage de secret à la volée
- Mettre en place un serveur vault avec l’option ui configurée
- Connecter le module terraform au serveur vault
- Faire en sorte que les clés api soient renseignées par vault et non pas vous ou vos variables terraform
- Faire une pull request sur master

### 📋 Consignes :
Pensez à commenter/versionner les scripts et à joindre des captures d’écran

### 🎯 Livrables :
- Le repo git
- Une organisation et un workspace connectée à ce repo git
- Le serveur vault
