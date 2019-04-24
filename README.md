# Cordova
Cordova est un outil qui permet de développer des applications mobiles en utilisant des langages webs : HTML, CSS et JavaScript. <br/>
Il utilise pour cela les composants webview des différents systèmes avec une sucouche permettant au JavaScript d'intéragir avec des fonctions systèmes.

### Création du projet

cordova create nomdufichier
cd nomdufichier
cordova platform add android
cordova platform add browser
cordova serve

cordova plugin add cordova-plugin-dialogs // utilise les alertes native des telephones

### Test sur android emulateur: 
- lancer android studio
- add device manager
- ajouter un nouveau support (exemple: oreo 8.0)
<br/>
- commande 1: cordova emulate android
- commande 1 (autre méthode): cordova run android
<br/>
** Le chemin d'accès vers la version apk est indiqué dans "Built the following apk(s): /adresse" **