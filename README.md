<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Description du projet

## Objectif

Il sʼagit dʼun test de recrutement afin dʼintégrer lʼéquipe de Kaffein Agency en tant que
développeur Back ou Fullstack.  
Le client fictif utilise le CRM hubspot, et souhaite mettre à disposition de ses commerciaux une
plateforme de visualisation des entreprises et contacts du CRM. 

-----------------

## Création du projet

Utilisation de __Composer__ pour la création de ce projet __Laravel__.

Commande : 
`composer create-project --prefer-dist laravel/laravel name`

-----------------

## Versions

* PHP 8.2.6
* Composer 2.5.5
* Laravel 10.10.1
* Node 16.15.1
* MariaDB 10.10.2

-----------------

## Commandes

Serveur Web __PHP__ : `php artisan serve`  
Serveur __NPM__ en dev : `npm run dev`  
Migration des données : `php artisan migrate`

-----------------

## Base De Données

Actuellement, il existe une seule BDD (tout en local bien-sûr) du nom de *entreprise_auth*.  
Cette base va contenir les comptes permettant la connexion à l'application.

-----------------

## Authentification

Pour gérer la partie d'authentification, j'utilise la librairie __UI__ de __Laravel__.  
Lien [Github](https://github.com/laravel/ui).  

`composer require laravel/ui`

Dans la cas d'utiliser de __VueJS__ pour le développement Front, on va utiliser la commande suivante pour intégrer l'authentification :  
`php artisan ui vue --auth`  

Ensuite, je vais installer la libraire avec __NodeJS__ :  
`npm install`  
Et ensuite je vais pouvoir lancer le serveur local :  
`npm run dev`
