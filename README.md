# Projet Next.js de Connexion de Wallet

Ce projet Next.js est une application conçue pour permettre aux utilisateurs de connecter leur portefeuille (wallet) crypto et d'afficher leur adresse ainsi que le nombre de jetons (tokens) crypto qu'ils détiennent. Pour l'instant, seul le token Ethereum et le token Sepolia sont pris en compte.

En plus de la fonctionnalité de connexion de portefeuille, l'application offre également une fonctionnalité de conversion de devises, permettant aux utilisateurs de convertir des euros en Ethereum et vice versa.

## Installation

1. Clonez ce dépôt sur votre machine locale :

`git clone https://github.com/BAMBA-FALL/cryptoapp.git`


2. Accédez au répertoire de votre projet :

`cd CryptoApp`


3. Installez les dépendances :

`npm install`

4. Installez les dépendances :

Pour se connecter à son wallet, installe l'extension métamask sur ton navigateur et crée un compte.
* Ce compte métamask n'est juste qu'un compte de teste ne met pas ton argent dedans.

## Démarrage du Projet

Une fois les dépendances installées, vous pouvez démarrer le projet en utilisant la commande suivante :

`npm run dev`


Cette commande démarre l'application en mode développement. Ouvrez votre navigateur et accédez à l'URL [http://localhost:3000](http://localhost:3000) pour voir l'application en action.

## Fonctionnalités

- Connexion de Wallet : Les utilisateurs peuvent se connecter à leur portefeuille crypto et afficher leur adresse ainsi que le nombre de jetons qu'ils détiennent.
- Conversion de Devises : Les utilisateurs peuvent convertir des euros en Ethereum et vice versa.

## Technologies Utilisées

Ce projet est développé en utilisant les technologies suivantes :

- **Next.js** : Framework React pour le développement côté client et côté serveur.
- **coinstats** : API pour obtenir les prix de l'ether.
- **EtherJs** : Bibliothèque JavaScript pour l'interaction avec les contrats intelligents Ethereum.
- **useDapp** : Pour se connecter à son wallet.
- **Tailwind CSS** : Framework CSS utilisé pour styliser l'interface utilisateur.
- **ChakraUI** : Framework CSS utilisé pour styliser l'interface utilisateur.
- **Shadcn** : Framework CSS utilisé pour styliser l'interface utilisateur.
