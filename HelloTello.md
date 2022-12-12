# Hello Tello


Bienvenu à vous dans ce tutorial d'initation au Tello et par où commencer pour absorder ça programmation.

Le Tello est ce petit drone créé pour une utilisation educative.

Il y a deux modèles, le Tello et le Tello EDU.

Si votre but c'est juste de vous amusez avec le drone le Tello suffit.
Le Tello EDU à deux trois petits avantages comme: une communication USB, une connexion à un routeur, un meilleur positionement,...


# Jouer un peu avec le drone

## Wifi Connection

Avant tout chose.
Un drone est controllé soit par Bluetooth < 10 mètres, Wifi < 10-50 mètres, FM 100+ mètres, 4G/GPS.
Dans notre cas, le drone Tello utilise le Wifi qu'il créé pour communiquer.

Vous devez donc connecter votre ordinateur, ou téléphone, au Drone pour que l'application puisse communiquer avec le Drone.
Le nom du Wifi sur lequel vous devez vous connctez ressemble à ceci: TELLO-NNNNNNN
((Ajouer une image))

Pour les plus informaticiens, la communication est en UDP et vous pouvez trouvez le manuel ici:
((Ajouter le PDF du Tello))
_(Plus sur la partie programmation dans la partie avancée du tutorial.)_

Attention que le drone à une mise en veille. Après N minutes sans commandes reçu, le drone coupe la connection et se coupe.
Maintenant 

## Applications

### Juste pour jouer
Mobile: 
- Tello : Vous permet de faire volez le Tello, de prendre des photos et vidéos.


Window:
- FPV steam /origin: Une application qui permet de s'entrainer à controller des drones via une simuation réaliste.


### Educative
Mobile: 
- DroneBlocks : Une application educative qui permet de controller le votre drone comme pour l'applicatoin Tello. Mais elle permet aussi d'assembler des blocks de logique pour "programmer" un chemain à prendre.

Window:
- DroneBlocks : Même application que pour Mobile mais sur ordinateur (tourne comme une extension de Chrome)
- Scratch 2: Vous pouvez apprendre avec vos enfants à programmer votre drone avec des simples blocks "comme des legos"  (Attention il faut installer Node.js et Adobe AIR)
- Scratch 3: version Tello: Meme chose que Scratch 2 en un peu plus beau. La version Tello est un version constructeur avec tout ce qu'il faut déjà dedans.
- Unity 3D: À l'aide d'un code fournit sur internet vous pouvez programmer avec du code réel si vous êtes dévelopeur de métier. Plus dans la partie avancée du cours. ((Code GitHub))


## Les comamndes principales

Lors d'une utilisation d'un Drone en non FPV, il n'y a pas énormément de commande:
Yaw, Rall, Pitch, Throttle, Armed ,Take Off, Land.
- Yaw:  Tourner de gauches à droites
- Pitch: Incliner vers l'avant et l'arriègre
- Throttle: Montez et descendre 
  - Augment/Diminue la poussée de tout les moteurs


### Les moteurs derrières ces commandes

Les commandes précédentes est une interface pour simplifier la vie des utilisateurs. Vous n'avez pas besoin de controller les moteurs.
Mais comment ceux-ci fonction ?

Q: Peut on controller les moteurs du Tello directement?
A: Malheureusement et heureusement: non.



-------

# App Mobile: Tello

Cette application vous permet de controller votre drone depuis Android.
((Ajouter des photos de l'application et de son interface))

# App Desktop: DroneBlocks 

((Ajouter des photos de l'application et de son interface))



--------------

# RTFM
- Le manuel utilisateur du Tello: https://dl-cdn.ryzerobotics.com/downloads/Tello/Tello%20User%20Manual%20v1.4.pdf
- Le manuel pour développeur Tello: https://dl-cdn.ryzerobotics.com/downloads/Tello/Tello%20SDK%202.0%20User%20Guide.pdf



# Code online

- Controllez le Tello avec Android ou C#
  - https://github.com/Kragrathea/TelloLib 