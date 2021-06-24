# Install & Setup [WordPress](http://wordpress.org) 

Author: [Anas Labzar](https://github.com/AnasLabzar)

##  How To Install WordPress 

## Synopsis

I was looking around for a useful script to speed up the setting-up process for a WordPress site.

After looking around, I found a couple of great scripts by [@snaptortoise](https://github.com/snaptortoise) and [@darlanrod](https://github.com/darlanrod). However I needed more features to speed up my day-to-day WordPress work, so I built on top of the fantastic work these guys did to get it to where I needed it to be.


# Installation

si vous êtes à l’aise avec ce type d’installation, voici la version rapide des instructions. Les instructions détaillées se trouvent à la suite.

Téléchargez et décompressez l’archive ## WordPress ;
Sur votre serveur, créez une base de données ainsi qu’un utilisateur MySQL ou MariaDB qui a tous les privilèges pour y accéder et la modifier ;
Facultatif : renommez le fichier wp-config-sample.php en wp-config.php, puis modifiez ce fichier pour y ajouter vos informations de base de données.
Note : vous pouvez sauter cette étape si besoin, le programme d’installation créera le fichier wp-config.php pour vous s’il n’existe pas ;
Téléversez les fichiers WordPress (à l’exception du répertoire WordPress lui même) à l’emplacement voulu sur votre serveur :
Pour installer WordPress à la racine de votre nom de domaine (par exemple example.com), placez les fichiers dans le répertoire racine de votre serveur ;
Pour installer WordPress dans son propre répertoire (par exemple example.com/blog/), créez le répertoire blog sur le votre serveur et placez-y les fichiers ;
Note : si votre client FTP a une option pour convertir les noms de fichier en minuscules, assurez-vous qu’elle est désactivée ;
Accédez à l’URL où vous avez placé les fichiers WordPress pour lancer le programme d’installation :
https://example.com si vous avez installé WordPress dans le répertoire racine ;
https://example.com/blog/ si vous avez installé WordPress dans son propre répertoire ;
C’est terminé ! WordPress devrait maintenant être installé.


## Plugins
The script installs the following WordPress plugins:

Advanced Custom Fields †
ACF Content Analysis for Yoast SEO
Contact Form 7
Flamingo
W3 Total Cache
Wordfence Security
Yoast SEO
† I highly recommend purchasing the Pro version!
