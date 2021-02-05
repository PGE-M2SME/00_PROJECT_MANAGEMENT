# 01_PROJECT_MANAGEMENT

# Equipes

IHM |Analyse|Generation| PC-uC  |Integration STM32|	Integration FPGA    | BUS_COM
---------|-------|---------------|---------------------|-----------------|----------|----------
Manoah 	:mag_right: |Ryan	 :page_with_curl: :mag_right:|Xavier :page_with_curl: |Youssef :page_with_curl:|Clément	|Thomas | Bruno :page_with_curl:
Bouchra	 :page_with_curl:|Mehdi	 |Alejandro	:mag_right: |Farouk	| | | Alexandre	
Soufiyane|Badr	 |Haitem	| | | | Jayendra
   x  |Anass |Yasmine	| | | | 		
   x | Nijad | | | |

Responsable documentation : :page_with_curl: </br>
Responsable démonstration : :mag_right:

# Etat d'avancement de la partie software avec objectif pour la semaine
# Dernière MAJ : 25/01

## IHM

### Ce qui est en train d'être fait :
- Gautier teste l'ecran
- Manoah prend en main le logiciel Workshop 4D

Git de developpement : https://github.com/PGE-M2SME/12_IHM

## BUS COM

### Ce qui doit être fait
- Algorithme de détection entre le bus SPI et I2C

Note : Cette partie est un travail de recherche, nous allons essayer de faire un maximum du cahier des charges. Pour cette semaine nous allons essayer de detecter un message SPI et I2C

Git de developpement : https://github.com/PGE-M2SME/08_BUS_COM

## Liaison FPGA - Micro-controleur

### Ce qui devait être fait (Objectif semaine du 25/01):

Communication SPI STM32
- Rendre le code accessible par une libraire
- Définir les fonctions d'accès à la libraire avec paramètres
- Documentation : Décrire les fonctions avec leurs I/O
- Documentation : Décrire comment importer la libraire et comment se servir des fonctions

Communication SPI FPGA
- Regarder comment faire une interruption (facultatif)
- Rendre le code accessible par un component
- Documentation : Décrire le component avec leurs I/O
- Documentation : Décrire comment câbler le component et comment s'en servir

Git de developpement : https://github.com/PGE-M2SME/09_COM_FPGA_uC

## Alanyse de flux

Git de developpement : https://github.com/PGE-M2SME/10_FPGA_ANALYSE

## Generation de flux

### Ce qui devait être fait (Objectif semaine du 25/01):

- Identifier les entrées (vecteur de combien de bits  correspond à quoi..etc) influence quelle sortie 
(voir tuto diamond si on peut voir les blocs)
- Trouver une solution sur comment changer les paramètres de la mire dans le code
- A la fin :
faire une documentation pour l'équipe IHM 

Git de developpement : https://github.com/PGE-M2SME/11_FPGA_GENERATION

