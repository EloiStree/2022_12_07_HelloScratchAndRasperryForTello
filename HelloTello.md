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

Pour les plus informaticiens, la communication est en UDP et vous pouvez trouvez le manuel ici:
[Developer Manuel via UDP](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi-ic3s8fP7AhUXHOwKHVQpBuoQFnoECBsQAQ&url=https%3A%2F%2Fdl-cdn.ryzerobotics.com%2Fdownloads%2FTello%2FTello%2520SDK%25202.0%2520User%2520Guide.pdf&usg=AOvVaw3ITPkQs2PW2xA9Ig5WtR0g)
_(Plus sur la partie programmation dans la partie avancée du tutorial.)_

Attention que le drone à une mise en veille. Après N minutes sans commandes reçu, le drone coupe la connection et se coupe


## Applications

### Juste pour jouer
Mobile: 
- Tello : Vous permet de faire volez le Tello, de prendre des photos et vidéos.
[![image](https://user-images.githubusercontent.com/20149493/207022258-b3aa5dbf-c96e-4600-bc99-92b68e511657.png)](https://www.dji.com/be/downloads/djiapp/tello)  
Download [iOs](https://apps.apple.com/app/tello/id1330559633) [Android](https://service-adhoc.dji.com/download/app/android/ba88a046-6f7e-4cbb-a969-27851eb4bbf5): https://www.dji.com/be/downloads/djiapp/tello


Window:
- DroneBlocks sur Chrome : https://chrome.google.com/webstore/detail/droneblocks/nbfahmffcopanponfpkefngbijhbnffa
- Drooone:   https://apps.microsoft.com/store/detail/drooone/9N0Z6WVT0W6N?hl=fr-be&gl=be
- FPV steam /origin: https://www.liftoff-game.com/
  - Une application qui permet de s'entrainer à controller des drones via une simuation réaliste.



### Educative
Mobile: 
- [DroneBlocks](https://play.google.com/store/apps/details?id=com.unmannedairlines.droneblocks) : Une application educative qui permet de controller le votre drone comme pour l'application Tello. Mais elle permet aussi d'assembler des blocks de logique pour "programmer" un chemain à prendre.
[![image](https://user-images.githubusercontent.com/20149493/207022642-233dccd6-4593-445a-b891-ae9bfb2e60ff.png)](https://play.google.com/store/apps/details?id=com.unmannedairlines.droneblocks)


Window:
- [DroneBlocks](https://chrome.google.com/webstore/detail/droneblocks/nbfahmffcopanponfpkefngbijhbnffa) : Même application que pour Mobile mais sur ordinateur (tourne comme une extension de Chrome)
  - Video: https://youtu.be/0W_7TGhhdGM 
- Scratch 2: Vous pouvez apprendre avec vos enfants à programmer votre drone avec des simples blocks "comme des legos"  (Attention il faut installer Node.js et Adobe AIR)
  - Video: https://www.youtube.com/watch?v=6g-2U_lh_q4
- Scratch 3: version Tello: Meme chose que Scratch 2 en un peu plus beau. La version Tello est un version constructeur avec tout ce qu'il faut déjà dedans.
  - Video: https://www.youtube.com/watch?v=dQ8mZ0Q0YHs 
- Unity 3D: [Code GitHub](https://github.com/comoc/TelloForUnity) À l'aide d'un code fournit sur internet vous pouvez programmer avec du code réel si vous êtes dévelopeur de métier. Plus dans la partie avancée du cours
  - Video: https://www.youtube.com/watch?v=dQ8mZ0Q0YHs

## Les comamndes principales

Lors d'une utilisation d'un Drone en non FPV, il n'y a pas énormément de commande:
- Yaw, Rall, Pitch, Throttle, Armed ,Take Off, Land.
  - Pour le control libre
- Go To, Speed, Flip , Glide 
  - pour les controles à l'aide de coordonnées. 

- Throttle: Montez et descendre 
  - Augment/Diminue la poussée de tout les moteurs
- Pitch: Incliner vers l'avant et l'arriègre
  - Diminue la rotation des deux monteurs avant ou arrières
- Roll: Incliner vers la gauche et la droite
  - Diminute la rotation des deux moteurs de gauches ou de droites
- Yaw: Tourner de gauches à droites
  - Change la rotation des moteurs en diagonales

![image](https://user-images.githubusercontent.com/20149493/207021135-4d1ac17d-a970-43b2-875c-3bc77c583f46.png)


### Les moteurs derrières ces commandes


Q: Doit-on/ Peut-on controller les moteurs du Tello directement?
A: Malheureusement et heureusement: non.

Les commandes précédentes sont de fonction d'un interface pour simplifier la vie des utilisateurs. Vous n'avez pas besoin de controller les moteurs.

Si vous êtes curieux de ce qui se passe niveau des moteurs quand vous le controller, je vous invite à regarder cette video sur le sujet: https://youtu.be/1GNwMhPwFiE?t=307


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
  - Démo donné par le manuel en Python: https://dl-cdn.ryzerobotics.com/downloads/tello/20180222/Tello3.py

## Command principale
![image](https://user-images.githubusercontent.com/20149493/207014496-8456008e-52d0-4ee3-adac-7477cc12b7e2.png)
![image](https://user-images.githubusercontent.com/20149493/207014572-0a8b4bfc-701b-44fd-9ce3-b3a747c94447.png)
![image](https://user-images.githubusercontent.com/20149493/207014069-d56400e2-dddd-4abb-943a-eacfa1b98069.png)

Ne fonction que si le drone à des coordonnées X,Y,Z:
![image](https://user-images.githubusercontent.com/20149493/207014778-a90e873d-4a8f-46d4-a893-1754401d71d4.png)

Établir une communication avec le drone:
![image](https://user-images.githubusercontent.com/20149493/207015485-843814cd-b3ed-4840-ba24-f99965b26553.png)


# Code online

- Controllez le Tello avec Android ou C#
  - https://github.com/Kragrathea/TelloLib 
- Code qui englobe TelloLib dans Unity 
  - https://github.com/comoc/TelloForUnity  
- Video et code d'un Youtuber connu dans la VR pour controller un drone
  - Video: https://youtu.be/E45TzK176IU
  - Code:  https://github.com/dilmerv/OculusPassthroughDrone
 
