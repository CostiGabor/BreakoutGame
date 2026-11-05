# Casse-briques (Breakout Game) - JavaFX

Un jeu d'arcade classique développé en Java utilisant la bibliothèque JavaFX. Le joueur contrôle une raquette pour faire rebondir une balle et détruire un mur de briques généré aléatoirement.

##  Fonctionnalités
* **Génération de niveau aléatoire :** Le jeu génère un mix de briques normales et de briques solides.
* **Briques à résistance multiple :** Les briques solides nécessitent 3 coups pour être détruites, avec un changement de couleur visuel à chaque impact.
* **Gestion avancée des collisions :** Détection précise des collisions sur les 4 côtés des objets (haut, bas, gauche, droite) pour inverser correctement la trajectoire de la balle.
* **Double contrôle :** La raquette peut être contrôlée à la fois via la souris et via les flèches du clavier.

## 🛠 Stack Technique
* **Langage :** Java
* **Interface Graphique :** JavaFX
* **Architecture :** Programmation Orientée Objet (Classes abstraites, Interfaces, Héritage)

## ⚙ Installation et Lancement
1. Assurez-vous d'avoir le JDK Java et le SDK JavaFX installés.
2. Clonez le dépôt : `git clone https://github.com/CostiGabor/BreakoutGame.git`
3. Lancez la classe principale `BreakoutGame.java` depuis votre IDE préféré (IntelliJ IDEA, VS Code ou Eclipse).