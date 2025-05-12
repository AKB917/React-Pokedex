# React-Pokedex
Pokédex React – Projet API PokéAPI
Description

Ce projet est une application web développée avec React permettant d'explorer l'univers des Pokémon via la PokéAPI.
L'application affiche les Pokémon par tranches de 15. Au chargement initial, les 15 premiers Pokémon s’affichent automatiquement. Un bouton “Next” permet de charger les 15 suivants à chaque clic, en les ajoutant à la suite de la liste existante.

Ce projet a été initialement conçu en JavaScript Vanilla, puis réécrit avec React dans une logique de composant pour une meilleure organisation du code et une gestion fluide de l'état.
Fonctionnalités

    Affichage dynamique des Pokémon depuis la PokéAPI

    Chargement progressif par tranches de 15 via un bouton “Next”

    Affichage du nom, type et sprite de chaque Pokémon

    Style visuel différencié en fonction du type de Pokémon

Technologies utilisées

    React (Next.js)

    CSS Modules

    PokéAPI (https://pokeapi.co)

Structure des composants

    Home.js : récupère et stocke les données des Pokémon via fetch et les affiche avec le composant Pokemon

    Pokemon.js : composant affichant une carte Pokémon avec son nom, son image, et son type

    styles/ : contient les styles CSS modulaires de l’application

    pages/index.js : point d'entrée Next.js important pour rendre la page d’accueil

Lancer le projet

    Cloner le dépôt :

git clone <lien-du-repo>
cd <nom-du-projet>

    Installer les dépendances :

yarn install

    Lancer le serveur de développement :

yarn dev

    Ouvrir le navigateur à :

http://localhost:3000

Remarques

    Le projet utilise useEffect pour charger les données à la première ouverture.

    Une pagination simple est mise en œuvre en incrémentant l’index de départ.

    Le style de chaque carte Pokémon est lié à son type (couleurs personnalisées).

	