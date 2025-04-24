# test-unitaire-php-debutant
Job02 Jour 02 Apprentissage des Tests Unitaires dans le Code.

Préparation du dossier TEST-UNITAIRE-PHP-DEBUTANT
Création du dossier Pictures (où seront stockées les copies-écran illustrant le README)

Installation du composer.json et composer.lock à partir du Bash, dans le Terminal (Rappel : ces fichiers permettront à ???????????????) : 

composer require --dev phpunit/phpunit    [pour installer les 2 fichiers composer]

![alt text](Pictures/composerJsonInstall.PNG)


composer init   [pour choisir des dépenses à installer, si nécessaire, donc qui ne seraient pas incluses dans le composer.lock]

![alt text](Pictures/composerInit1.PNG)


composer install (pour installer les dépenses sélectionnées)

![alt text](Pictures/composerInstall.PNG)


Dans le fichier Math.php, création de la classe Math avec la fonction addition.

![alt text](Pictures/classMathPhp.PNG)

Dans le fichier MathTest.php, création du Test Unitaire pour vérifier l'exactitude de ma fonction : 

![alt text](Pictures/classMathTestPhp.PNG)

Lancement du test PHPUNIT pour vérifier l'exactitude du calcul : 

vendor/bin/phpunit tests

Le test est passé avec succès : ![alt text](Pictures/phpUnitSuccessful.PNG)

Le test échoue (j'ai rajouté un 1 dans mon calcul) : ![alt text](Pictures/classMathPhpFailure.PNG)

![alt text](Pictures/phpUnitFailure.PNG)

