# Guide d'installation de LAMP sur WSL

## Préambule

Suite à l'utilisation de WAMP sous Windows, je suis venu à la conclusion que le workflow n'était pas efficace. La performance de phpMyAdmin sous Wamp est __horrible__! C'est pourquoi que j'ai cherché pour une solution et la plus facile semblait d'utiliser LAMP sous WSL.

## Qu'est-ce que WSL

Le Sous-système Windows pour Linux permet aux développeurs d’exécuter un environnement GNU/Linux (et notamment la plupart des utilitaires, applications et outils en ligne de commande) directement sur Windows, sans modification et tout en évitant la surcharge d’une machine virtuelle traditionnelle ou d’une configuration à double démarrage.

## Démarrer avec WSL

Pour démarrer avec WSL, suivez-la [documentation officielle de Microsoft](https://docs.microsoft.com/fr-ca/windows/wsl/install-win10).

## Installation de LAMP sous WSL

Suivre la [procédure](https://www.how2shout.com/how-to/how-to-install-apache-mysql-php-phpmyadmin-on-windows-10-wsl.html) dans le guide.

Ajouter la [configuration](https://askubuntu.com/a/19128) `Apache` à phpMyAdmin.

[Configuration](https://stackoverflow.com/a/52335791) du mot de passe de l'utilisateur `root` pour permettre la connexion à phpMyAdmin.

Si vous avez un message d'erreur dans phpMyAdmin suite à l'exécution d'une requête, regardez cette réponse sur [stackover flow](https://stackoverflow.com/questions/48001569/phpmyadmin-count-parameter-must-be-an-array-or-an-object-that-implements-co).

## Références

- <https://docs.microsoft.com/fr-ca/windows/wsl/about>
- <https://docs.microsoft.com/fr-ca/windows/wsl/install-win10>

Tous droits réservés 2021 © Alexis Garon-Michaud
