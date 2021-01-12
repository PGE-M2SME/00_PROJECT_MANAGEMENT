# 01_PROJECT_MANAGEMENT

# Etat d'avancement de la partie software avec objectif pour la semaine
# Dernière MAJ : 08/01

## IHM

### Ce qui a été fait :
- Bonne prise en main de TouchGFX par Manoah avec une maquette 

### Ce qui est en train d'être fait :
- Bouchra va finir la conception visuelle de l'IHM
- Alejandro continue de prendre en main TouchGFX
- Soufiyane va recuperer et tester l'écran 

### Ce qui devra être fait :
- Validation de l'IHM par le client
- Lancement de fonctions a partir de TouchGFX
- Affichage de valeurs issue de fonctions sur TouchGFX

### Ce qui devait être fait (Objectif semaine du 11/01) :
-  Il n'y a pas encore de conception detaillé de l'IHM. On sait globalement ce qu'il y aura et quel services devrons être traités mais il n'y a pas d'idées sur les pages et le design. C'est une partie importante a faire comme ça lors du developpement en groupe il n'y aura pas de questions a ce poser.
Vous pouvez utiliser le logiciel "Balsamiq mockeup" en version d'essaie:
https://balsamiq.com/wireframes/
- Il faudra prendre en mail le logiciel TouchGFX pour être a l'aise avec l'environnement de developpement.

## BUS COM

### Ce qui a été fait :
- Communication bus SPI VHDL slave
- Detection théorique entre les bus

### Ce qui doit être fait
- Communication bus I2C VHDL slave
- Detection entre I2C et SPI

Note : Cette partie est un travail de recherche, nous allons essayer de faire un maximum du cahier des charges. Pour cette semaine nous allons essayer de detecter un message SPI et I2C

## Liaison FPGA - Micro-controleur

### Ce qui a été fait :
- Communication SPI FPGA -> Microcontoleur (STM32)
- Communication SPI Microcotroleur (STM32) -> FPGA

### Ce qui devait être fait (Objectif semaine du 11/01):
- Communication dans les 2 sens en SPI entre FPGA et micro-controleur

Git de developpement : https://github.com/PGE-M2SME/08_BUS_COM

## Alanyse de flux

### Ce qui a été fait :
- Les recherches sur les protocols de communication DVI et SDI (BNC)
- Diagramme des exigences
- Diagramme des cas de utilisation
- Installation de la machine virtuelle ( presque tous les membres du groupe )

### Ce qui doit être fait :
- Commencer à chercher L’ IP CORE SDI de lattice sur internet
- Se familiarise avec le logiciel diamond (logiciel de développement pour LATTICE)
- Étudier le guide d'utilisation lattice de cette IP

### Ce qui devait être fait (Objectif semaine du 11/01):
- Mise en oeuvre de la machine virtuelle
- Faire un projet DVI avec la carte altera. 
- Analyser les différents codes sur le git pour se familiariser avec les cartes lattice et l’environnement de développement diamond
- La partie conception sur magicDraw (en cours )

## Generation de flux

### Ce qui a été fait :
- La machine virtuelle a été démarré par la moitie des intégrantes du groupe.

### Ce qui est en train d'être fait :
- Nous avons repris le projet de Cyprien pour se familiariser avec l’outil Lattice.
- Demain une personne du groupe récupérera la carte chez Perico (message du 12/01)
- Chaque intégrant du groupe doit étudier l’ensemble du code

### Problèmes rencontrés :
- Pour la moitie du groupe, elles rencontrent un problème d’installation avec le logiciel. La dernière version de docker desktop a besoin de windows 10. Possible blocage jusqu’à la mise à jour de windows 10 sur ses ordinateurs portables ou une partition avec une version de linux.
- Une possible blocage avec toute la familiarisation de l’outil Lattice, pour surpasser ce problème les personnes avec le logiciel démarré devront mettre à jour aux autres.
-	Une personne du groupe va récupérer la carte de développement. Une possible blocage sera l’installation du driver pour téléverser le projet de Cyprien dans la carte mais nous allons avoir la carte d’abord.
-	Un défi du temps sera d’étudier toutes les lignes du code qui a été donné. Chaque intégrant devra identifier les sorties, entrées du projet aussi avec la compréhension de comment générer le 9 types de mires donne dans le code.

### Ce qui devait être fait (Objectif semaine du 11/01):
- Mise en oeuvre de la machine virtuelle
- Savoir creer un projet sous Latice : possibilité de reprendre le projet de Cyprien
- Mettre en oeuvre la carte de developpement (pour afficher la mir) : possibilité d'aller la chercher chez cyprien
-> Il faut determiner qui prend les cartes
- Comprendre le code VHDL (quelles sont les paramètres importants pour generer une mir


