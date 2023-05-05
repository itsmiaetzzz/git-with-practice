# Tutoriel Git

Ce tutoriel est conçu pour les débutants en Git qui souhaitent apprendre les bases de Git et de GitHub. Le tutoriel couvre les étapes suivantes :

1. Installation de Git
2. Configuration de Git
3. Création d'un dépôt Git
4. Ajout de fichiers au dépôt
5. Enregistrement des modifications dans Git
6. Publication des modifications sur GitHub

## Étape 1 : Installation de Git

Si vous n'avez pas encore installé Git sur votre ordinateur, vous pouvez télécharger la dernière version à partir du site officiel de Git : https://git-scm.com/downloads.

## Étape 2 : Configuration de Git

Avant de pouvoir utiliser Git, vous devez configurer votre nom d'utilisateur et votre adresse e-mail. Ouvrez une ligne de commande ou un terminal et entrez les commandes suivantes en remplaçant "votre_nom" et "votre_email" par votre nom d'utilisateur et votre adresse e-mail :

git config --global user.name "votre_nom"
git config --global user.email "votre_email"


## Étape 3 : Création d'un dépôt Git

Maintenant que Git est installé et configuré, vous pouvez créer votre premier dépôt Git. Pour créer un dépôt Git, ouvrez un terminal ou une ligne de commande Git et naviguez jusqu'au dossier où vous souhaitez créer votre dépôt. Entrez les commandes suivantes :

mkdir nom_du_depot
cd nom_du_depot
git init


Cela va créer un nouveau dossier "nom_du_depot" et initialiser un dépôt Git à l'intérieur.

## Étape 4 : Ajout de fichiers au dépôt

Maintenant que vous avez créé votre dépôt Git, vous pouvez y ajouter des fichiers. Pour ajouter des fichiers, copiez-les simplement dans le dossier du dépôt que vous venez de créer. Vous pouvez également utiliser la commande `git add` pour ajouter des fichiers spécifiques. Par exemple, si vous avez un fichier appelé "mon_fichier.txt" que vous souhaitez ajouter, entrez la commande suivante :

git add mon_fichier.txt


## Étape 5 : Enregistrement des modifications dans Git

Une fois que vous avez ajouté des fichiers à votre dépôt, vous pouvez enregistrer les modifications en utilisant la commande `git commit`. Pour enregistrer tous les fichiers qui ont été ajoutés à votre dépôt, entrez la commande suivante :

git commit -m "Premier commit"


Cela enregistrera les modifications dans Git avec un message de commit "Premier commit".

## Étape 6 : Publication des modifications sur GitHub

Maintenant que vous avez enregistré les modifications dans Git, vous pouvez les publier sur GitHub. Pour publier les modifications, vous devez d'abord créer un nouveau référentiel sur GitHub. Suivez les étapes ci-dessous pour créer un référentiel :

1. Connectez-vous à votre compte GitHub.
2. Cliquez sur le bouton "+" en haut à droite de l'écran et sélectionnez "Nouveau référentiel".
3. Donnez un nom à votre référentiel et cliquez sur le bouton "Créer un référentiel".

Une fois que vous avez créé votre référentiel, vous pouvez publier les
