# 2022-2023-4GP-Thang-Tien

# 1. Contexte et objectifs du projet
- [x] Réaliser une jauge de contrainte low-tech à base de graphite: [Pencil Drawn Strain Gauges and Chemiresistors on Paper](https://www.researchgate.net/publication/259846610_Pencil_Drawn_Strain_Gauges_and_Chemiresistors_on_Paper)
- [x] Concevoir un shield Arduino contenant l'amplificateur du capteur et les composants électroniques annexes (émetteur/récepteur Bluetooth, encodeur rotatif et écran OLED)
- [x] Réaliser une application mobile connectée à l'émetteur Bluetooth du capteur sous APP MIT INVENTOR 
- [x] Effectuer une évaluation du capteur sur un banc d'essai afin de produire une fiche technique et de comparer la technologie utilisée avec celle d'un autre capteur commercial similaire

# 2. Capteur de contrainte
> Notre capteur de contrainte utilise une jauge en papier dotée d'un circuit résistif en graphite, qui présente l'avantage d'être facile à mettre en place à faible coût. 
> La théorie de la percolation est exploitée dans ce capteur low-tech, qui est composé de nanoparticules de graphite formant des feuillets. Le réseau percolé caractéristique de la fine couche de graphite déposée sur la feuille de papier permet le transport des électrons entre les nanoparticules par l'effet tunnel. La déformation de la jauge en tension ou en compression entraîne une variation de la résistance de la couche de graphite, ce qui permet de mesurer la contrainte et la déformation appliquées.
> Le fonctionnement de notre jauge de contrainte repose sur la variation de la résistance du circuit résistif en fonction de sa déformation. Elle est alimentée par une tension régulée de 5V fournie par une carte Arduino UNO. Le courant circulant dans la jauge est mesuré pour fournir le signal du capteur, qui doit ensuite être amplifié et filtré.
  ## 2.1. Circuit amplificateur
  ## 2.2. Intégration Arduino
 > <div class="row" align="center">
 > <img src="image Kicad projet/pcb imprimé.PNG"/>
 > </div>
 
**Figure 4 - Design du PCB **

> <div class="row" align="center">
 > <img src="image Kicad projet/Circuit imprimé.jpg"/>
 > </div>

**Figure 5 - Circuit intergré des composants ** 

# 3. Programme Arduino
# 4. Application mobile
> Dans le cadre de ce projet, nous avons programmé sur MIT APP INVENTOR, l'application mobile connectée au module Bluetooth du capteur. Cette dernière est constituée d'une seule activité sur laquelle il est possible d'acquérir les données du capteur en temps réel et de les tracer sur un graphique dynamique.
 > <div class="column" align="center">
 > <img src="" alt="300" width="300"/>
 > <img src="" alt="300" width="300"/>
 > </div>

 **Figure 6 - page d'accueil de la dernière version de l'application mobile. Cette capture d'écran a été prise pendant le fonctionnement du capteur.**

 > Pour la connection Bluetooth, le smartphone doit être appareillé au module du capteur avant de pouvoir se connecter via l'application mobile. L'application ne permet pas de choisir à quel module se connecter. En réalité, l'application est liée à un module bluetooth en particulier (celui fourni avec le capteur) et lui seul pourra être connecté au smartphone pour la transmission de données. Une piste d'amélioration consiste à afficher la liste des dispositifs appareillés pour se connecter au module souhaité. Nous n'avons cependant pas pu implémenter cette fonctionnalité par manque de temps.

 > N.B: le fichier .apk de l'application mobile est situé dans le répertoire suivant: ....... .
# 5. Mesures : Banc de test, datasheet et discussions
  ## 5.1. Banc de test
  ## 5.2. Mesures et résultats
  ## 5.3. Datasheet
  ## 5.4. Discussions
  
