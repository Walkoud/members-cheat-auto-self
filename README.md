
# Members+ Cheat AUTO SelfBot

A tool to join tokens automaticly on a servers to farm coins !

Server discord: https://discord.gg/pcQz9AJ

Besoin de nodejs et de git installé sur votre Windows <br/>
Need NodeJs and GIT in Windows


## Installation Windows
-Download the zip https://github.com/Walkoud/members-cheat-auto-self/archive/master.zip <br/>
Téléchargez le zip https://github.com/Walkoud/members-cheat-auto-self/archive/master.zip <br/>

-Download Nodejs [Node.js](https://nodejs.org/) v4+ to run. <br/>
-Téléchargez Nodejs  [Node.js](https://nodejs.org/) version 4 ou + .

-Download Git for Windows [Git](https://git-scm.com/download/win) <br/>
-Télécharger Git pour Windows [Git](https://git-scm.com/download/win) 

-Cliquer sur le fichier Install et Install2 pour installer les fichiers du bots <br/>
-Click on Install.bat and Install2.bat to install  <br/>

-Pour démarrer le bot, cliquez sur run.bat <br/>
-Click on run.bat to boot the bot <br/>

N'oubliez pas de changer votre configuration dans le config.json !<br/>
Don't forget to change your configuration in config.json!

## Installation Linux or Termux (Android)
Possibilité de lancer sur Android avec l'application Termux <br/>
dans ce cas installez git en utilisant les commandes (dans le dossier du selfbot)
```sh
$ apt update && apt upgrade
$ termux-setup-storage
$ apt-get install git
$ git clone https://github.com/Walkoud/members-cheat-auto-self
$ apt-get install nodejs
$ cd members-cheat-auto-self
$ npm install
$ npm install discord.js@11
$ node index.js
```
N'oubliez pas de changer votre configuration dans le config.json ! <br/>
Don't forget to change config.json !

### Configuration TOKEN , PAY_ID , RESTARTAUTO,  WORK_TOKENS

Ouvrez config.json du dossier, puis changez le [token](https://youtu.be/2GBOYptubk4) en la votre, <br/>
les tokens des travailleurs (vos doubles comptes), <br/>
le payid (l'id de la personne à qui vous voulez payer), <br/>
le restartauto true ou false (True = rédémarrage automatique des tokens, False = l'inverse).

Open folder config.json, then change the [token](https://youtu.be/2GBOYptubk4) to your own, <br/>
Change the tokens workers (your alt account) <br/>
Change the paydid (id of who want to pay coins) <br/>
Change the restartauto, true or false (true to reboot automaticly tokens) <br/>




### Pour avoir son token et id sous android
 
 ##### Pour le token de votre compte
 
Téléchargez https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8

Puis installez l'apk, ouvrez l'application, puis appuyez sur la petite flèche en haut à gauche, cliquez sur Token Track, puis mettez vos identifiants discord, puis cliquez sur Track Token, et voilà vous aurez votre token affiché devant vous.

##### PAY ID IN CONFIG.JSON

FRANCAIS: Avoir l'id de la personne à payer les coins, [clique ici](https://support.discord.com/hc/fr/articles/206346498-O%C3%B9-trouver-l-ID-de-mon-compte-utilisateur-serveur-message-#:~:text=Pour%20l%27ID%20d%27un,la%20zone%20du%20message%20textuel)

ENGLISH: To get id of user to pay : [click here](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

TURKCE: Parayi id'ye vermek için: [bas bana](https://support.discord.com/hc/tr/articles/206346498-Kullan%C4%B1c%C4%B1-Sunucu-Mesaj-ID-sini-Nerden-Bulurum-)
