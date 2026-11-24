ACCI - Gestin d'acte d'état civil

Présentation 

ACCI est un projet qui viens resoudre un besoin réel des population, réalisé dans cadre du cours  
de programmation web, mobile des étudiants de GSI 3 de l'écloe Superieure de Transport de Commerce d'Ambam.

Architecture technique

Le projet est orginsé en trois applications notamment:
-api/: backend et API developpés avec Laravel
-web/: interface web developpée avec React et vite
-mobile/: application mobile developpée avec Flutter

Prérequis
°PHP
°Composer
°Node.js et npm
°Flutter et Dart
°Git

Installation 

Backend Laravel

cd api, cd api
composer install
cp .env.example .env
php artisan key:generate
 Avec .env nous avons procédé à la configuration des parametes de notre base de données

Interface web React
 cd web
npm install
npm run dev

Application mobile Flutter
cd mobile
flutter pub get 
flutter run
 Organisation de Git
°main : branche principal stable
°develop : branche d'integration des développements.
°feature/* : branches dediées aux nouvelles fonctionalités.

Documentation 
Consulter le fichier CREDITS.md et le dossier docs/ pour les informations complémentaires.
 
