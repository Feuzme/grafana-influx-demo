# Installation pour la formation

## Slack de la formation : 

https://join.slack.com/t/grafadev/shared_invite/enQtODkxOTAzMzY3MjE5LTgyYjUwNTJmODIyODBhZmY2ZjY0NDM0Y2EzYWUxNTIwMGFmMTk5ZTBhNWYzMGRhOTkxOWRiMDBmOGIzOWEyYzg

## Pour Windows 10 :

1. Préférer Windows 10 pro car docker est plus facile à mettre en place

2. télécharger et installer Node.js 12 LTS : https://nodejs.org/en/ 

3. Créer un compte Github et se connecter : https://github.com/join
   * Ne perdez pas vos identifiants !

4. Télécharger et installer VS code : https://code.visualstudio.com/
   * Plugins à installer :
     * https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack
     * https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
     * https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
     * https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets

5. Docker 
   1. si vous voulez utiliser **Virtual box** --ou-- que vous utilisez **Windows 10 famille** : 
      * Si vous avez virtualbox déjà installé, il est conseillé de le désinstaller
      * Créer un compte Docker : 
      * Télécharger https://github.com/docker/toolbox/releases/download/v19.03.1/DockerToolbox-19.03.1.exe
      * Installer 
      * Lancer le lien docker sur le bureau, cela ouvre un terminal.
      * Laissez le temps au terminal de démarrer
      * Vous devriez voir une baleine en ASCII avec une IP en dessous
      * Ne fermez pas le terminal sinon cela arrête docker
    1. Si vous utilisez **Windows 10 PRO** avec **HyperV** (c'est HyperV ou Virtual box mais pas les deux)
       * cliquer sur le logo Windows (coin inférieur gauche de votre écran)
       * taper : ```hyperv```
       * Si vous voyez : gestionnaire HyperV, c'est qu'il est déja installé
       * Si vous ne voyez pas gestionnaire HyperV, cliquer sur activer/désactiver les fonctionnalités windows. Cocher Hyper-v puis redémarrer votre ordinateur
       * Installer docker : https://hub.docker.com/?overlay=onboarding
       * Rien de particulier à faire à part suivre les indications


## Pour Debian :

1. Installer Node.js : https://tecadmin.net/install-latest-nodejs-npm-on-debian/
   * S'arrêter avant la partie 4

2. Créer un compte Github et se connecter : https://github.com/join
   * Ne perdez pas vos identifiants !

3. Installer Docker
   * https://linuxize.com/post/how-to-install-and-use-docker-on-debian-10/
   * S'arrêter avant la partie Docker Images

4. installer docker-compose
   * https://docs.docker.com/compose/install/
 
5. Télécharger et installer VS code : https://code.visualstudio.com/ ou https://tecadmin.net/install-visual-studio-code-editor-ubuntu/
   * Plugins à installer :
     * https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack
     * https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
     * https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
     * https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets
  

## Pour Centos :

1. Installer Node.js : https://linuxize.com/post/how-to-install-node-js-on-centos-7/
    * S'arrêter avant "How to install Node.js and npm using NVM "

2. Créer un compte Github et se connecter : https://github.com/join
   * Ne perdez pas vos identifiants !

3. Installer Docker et docker compose
   * https://github.com/NaturalHistoryMuseum/scratchpads2/wiki/Install-Docker-and-Docker-Compose-(Centos-7)
 
4. Télécharger et installer VS code : https://code.visualstudio.com/ ou https://tecadmin.net/install-visual-studio-code-editor-ubuntu/
   * Plugins à installer :
     * https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack
     * https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
     * https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
     * https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets
  
## remarques

* Si vous utilisez Windows avec docker toolbox
n'installez pas vos projets docker en dehors des répertoires et sous répertoires /users . Si malgrè tout, vous voulez le faire ; voici la solution : https://stackoverflow.com/questions/34161352/docker-sharing-a-volume-on-windows-with-docker-toolbox
