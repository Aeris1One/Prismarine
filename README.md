----
# Bienvenue sur Prismarine ! #

----
## Qu'est-ce que Prismarine ? ##
Prismarine est une cryptomonnaie qui vise à réunir tous les serveurs Minecraft sous une monnaie unique !
Créee et maintenue par l'organisation The Elder Guardian, elle s'adresse à tous les Minecraftiens.

----
## L'obtenir! ##
Pour le moment, seul un client hors Minecraft est disponible, nous proposerons bientôt un launcher Minecraft ainsi qu'un mod permettant de miner des Prismarine.
  - *dépendances*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Démarrage! ##

  - cliquez sur l'icone PTR ou depuis la ligne de commande:
  - Unix/Linux: `./run.sh`
  - Window: `run.bat`

  - attendez que le wallet JavaFX s'ouvre
  - sur les plateformes sans  JavaFX, ouvrez http://localhost:7976/ dans un navigateur

----
## Compilez! ##

  - si nécessaire avec: `./compile.sh`
  - vous aurez besoin de JDK-8

----
## Débuguer le  PRS (Prismarine Reference Software) ##

  - Comment stopper le PRS ?
    - cliquez sur l'icone d'arret, ou éxecutez `./stop.sh`
    - ou si démarrez depuis la ligne de commande, utilisez ctrl+c ou fermez la fenetre.

  - Erreurs graphiques ou Stacktraces?
    - ouvrez une issue sur ce repo

  - Permission refusées (Permission Denied) ?
    - verifiez qu'il n'y as pas d'espaces ou de caractères non-latin dans le répertoire d'installation
    - il peut également s'agir d'une erreur connue de jetty

----
## Pour aller plus loin ##

  - dans ce dépot:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - Dossier doc/

----

## License
* Ce programme est sous licence Jelurida Public License version 1.1 pour la NXT Public Blockchain Platform.
