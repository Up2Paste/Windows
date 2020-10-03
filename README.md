Ceci est la version pour Windows de l'outil Up2Paste (U2P).

Up2Paste permet de créer un fichier au format Pastebin pour être utilisé avec vStream.

Cliquez ci-dessus sur le menu "Code" -> "Download ZIP".

Une fois décompressé sur votre PC, rendez-vous ici pour l'utilisation : 

https://github.com/Up2Paste/Windows/wiki/TUTORIAL-Up2Paste

0.9.6b
maj auto pastebin est une option
si des problemes de connexion 
mettre actif = 0
et copier les paste en manuel

Ajout chrome portable

1)installer GoogleChromePortable_85.0.4183.121_online.paf.exe
c'est la version 85 car elle est adaptée a chromedriver
Pour l'extraction elle se fait dans le rep U2P et changer le nom de:
GoogleChromePortable en => chromePortable

 
2)demarrer "seleniumPortable.exe" se connecter sur pasteBin et se logger
ensuite procedure normale pour U2P

ps: si par la suite ca bloque sur cloudflare en boucle, quittez U2P
demarrer "seleniumPortable.exe" se deconnecter et se reconnecter sur pasteBin.com
ensuite procedure normale pour U2P

correction anime de Episodes(p1) => Episodes(p01) 

0.9.5b
ajout masques Anime
correction maj auto pastebin

0.9.5a
coorection dict anime

0.9.5
ajout pris en charge nouveaux format express reg pour anime
filtre fichier anime rar, nfo etc 

nouveau format colonne
activation cast (acteur)
bridage a 2 fois pastebin auto en attendant reglemnt probleme


0.9.4a
correction pb maj pastebin serie

modif config

[Pastebin]
actif = 1
user =
password =
film =
serie1 =
serie2 =
anime =

[Cast]
16483 = Sylvester Stallone

[Config]
lang = fr
name = test
certification = 16
nbFormat = 0
majCast = 0 <=========

*regroupement pour paste

*onglet cast
vous mettrez la liste des acteurs sous la forme
numId = Nom acteur
numId 2 = acteur2
etc....

*dans[Config]
majCast = 0
0 => verifies qu il n'y a pas de nouveau acteur et ajoute si besoin
1 => efface la sauvegarde des acteurs et rescanne l'ensemble

pour l'instant ce ne créé qu 'une base qui sera exploiter pour des repertoires filmographies


<!--
**Up2Paste/Up2Paste** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
