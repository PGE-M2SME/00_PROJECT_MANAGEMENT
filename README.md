# 01_PROJECT_MANAGEMENT

# Etat d'avancement de la partie software avec objectif pour la semaine
# Dernière MAJ : 08/01

## IHM

### Ce qui a été fait :
- Sofiane a commencé un travail disponnible sur le GIT Disponnible sur une branche.
https://github.com/PGE-M2SME/03_SOFTWARE

### Ce qui doit être fait :
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
- Communication SPI FPGA -> Microcontoleur (Arduino) avec envoie en boucle
- Communication Microcotroleur (Arduino) -> FPGA

### Ce qui doit être fait
- Communication dans les deux sens avec un STM 32

Normalement le microcontoleur devrai bien être un stm32 Nucleo 144 (celui qu'on nous a donné l'année dernière)

Git de developpement : https://github.com/PGE-M2SME/08_BUS_COM

## Alanyse de flux

### Ce qui doit être fait :
- Mise en oeuvre de la machine virtuelle
- Faire un projet DVI avec la carte altera. 
- Analyser les différents codes sur le git pour se familiariser avec les cartes lattice et l’environnement de développement diamond
- La partie conception sur magicDraw (en cours )

## Generation de flux

### Ce qui doit être fait :
- Mise en oeuvre de la machine virtuelle
- Savoir creer un projet sous Latice : possibilité de reprendre le projet de Cyprien
- Mettre en oeuvre la carte de developpement (pour afficher la mir) : possibilité d'aller la chercher chez cyprien
-> Il faut determiner qui prend les cartes
- Comprendre le code VHDL (quelles sont les paramètres importants pour generer une mir


