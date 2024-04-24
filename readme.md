# Calculatrice Electron 

Bienvenue sur le ReadMe de mon projet Calculatrice Electron.
Ce projet est un portage d'un site HTML CSS JS en client lourd grâce à Electron.
Cette calculatrice permet de calculer un prêt immobilier et son ammortissement dans le temps

## Badges 

![texte_alternatif](https://img.shields.io/badge/build-passing-green "description du badge")


![Image calculatrice](https://github.com/SHarghel/CalculatriceElectron/blob/main/calc.png)

## prérequis

Nécéssite au minimum node avec la version v20.11.0 & v10.2.4

## Installation

**Note** : Ce tutoriel ne prends en compte uniquement les commandes sur Windows.

**1 :** Ouvrir un invite de commande et rentrer
```
git clone https://github.com/Sharghel/CalculatriceElectron.git
```
**2 :** S'assurer des bonnes versions de node & npm
```
node -v 
npm -v
```
**3 :** Depuis l'invite de commande suivre l'arborescence du dossier
```
cd CalculatriceElectron/my-electron-app/
```
**4 :** Installer le package Electron 
```
npm install --save-dev electron
```
Vous pouvez vous assurez du bon fonctionnement de l'installer grâce à la commande
```
npm start
```
**5 :** Concernant la distribution vous devez d'abord tout importer
```
npm install --save-dev @electron-forge/cli
npx electron-forge import
```
**6 :** Creation de la distribution avec
```
npm run make
```
Vous trouverez votre executable dans le dossier ```my-electron-app/out/calculatrice-win32-x64/```
avec le nom calculatrice.exe

## Utilisation

Cet executable peut vous servir dans le cas ou vous voulez calculer un prêt immobilier

## Roadmap

Fin du projet pour l'instant

## Contribution

Toute idées est bonne à prendre, n'hésiter pas de proposer.

## Auteurs et reconnaissance

Remerciement à Kevin Niel, notre intervenant pour la piste sur ce projet 