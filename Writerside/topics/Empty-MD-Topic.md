# Introduction

Bienvenue dans la documentation de l'API **Réservations de Vacances** ! Cette API, réalisée par **Florent GUYARD**, **Kilian PIFRE** et **Corentin Talour** dans le cadre de la formation Manager en Ingénierie Informatique option Lead Dev à IIA, permet aux développeurs d'interagir avec notre service pour faciliter la réservation de vacances.

## Fonctionnalités principales
- **Accès aux données** : Récupérez des informations complètes sur les réservations de voitures, d'avions et d'hôtels, ainsi que sur la gestion des utilisateurs.
- **Création et mise à jour** : Créez et mettez à jour des réservations pour les voitures, les avions et les hôtels, ainsi que pour la gestion des utilisateurs.

---

## Infos
Avant de commencer, assurez-vous de disposer des éléments suivants :
- **Base URL** : Toutes les requêtes doivent être envoyées à l'URL suivante : **http://localhost:8080/api/...**
- **Clé API** : Certaines routes nécessitent d'être connecté afin de pouvoir y accéder. Voici la route permettant de se connecter : **http://localhost:8080/api/user/auth**. Pour plus d'informations sur la connexion et la création d'un utilisateur, consultez la page [UserController](API_Reference6.md).

## Installation de l'API

### Prérequis API
Avant de commencer, assurez-vous d'avoir installé les outils suivants :
- **Java JDK** (version 17 ou supérieure)
- **Maven** (pour gérer les dépendances de l'API)
- **Git** (pour cloner le dépôt)

#### API

##### 1. Télécharger l'API

Pour télécharger l'API, vous pouvez cloner le dépôt Git à l'aide de la commande suivante :

```bash
git clone https://github.com/CorentinTalour/Projet_Grp_Java.git
```

##### 2. Configurer le projet

**Base de données : PostgreSQL**

Après avoir téléchargé l'API, suivez ces étapes pour la configurer :

1. Installez les dépendances Maven nécessaires.
2. Modifiez le fichier `application.properties` pour y indiquer votre nom d'utilisateur et votre mot de passe pour la base de données PostgreSQL.

Une fois ces configurations effectuées, vous serez en mesure d'exécuter l'API avec succès.

#### Front-end

### Prérequis front-end
Avant de commencer, assurez-vous d'avoir installé les outils suivants :
- **.NEt** (version 8 ou supérieure)
- **Visual studio** ou autre IDE **qui prend en charge .NET** afin d'utiliser **Blazor**.
- **Git** (pour cloner le dépôt)

##### 1. Télécharger le projet front-end

Pour télécharger le projet front-end, clonez le dépôt Git à l'aide de la commande suivante :

```bash
git clone https://github.com/kilianpfr/SiteReservation.git
```

##### 2. Lancer le projet

> Attention : N'oubliez pas de démarrer l'API en parallèle pour pouvoir exécuter les requêtes.
>
{style="warning"}

Ouvrez le projet dans un IDE compatible et exécutez le programme.