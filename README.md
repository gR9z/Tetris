# Tetris Game

## English Version

### Introduction
This personal project is a Java 17 implementation of the classic game Tetris. Developed independently at home for practice, it features a graphical user interface, game sound effects, music, and various Tetris pieces known as "minos." The project's architecture encompasses a variety of classes to manage game mechanics, user interactions, and graphical rendering.

### Key Features
- **Graphical User Interface**: Utilizes Java Swing for rendering the game board, next piece preview, and score display.
- **Sound Effects and Music**: Incorporates background music and sound effects for line clears and game over using the `Sound` class.
- **Versatile Mino System**: Includes multiple mino classes, such as `Mino_Bar`, `Mino_Square`, and `Mino_T`, each representing different Tetris pieces.
- **User Input Handling**: Processes keyboard inputs for piece movement and rotation through the `KeyHandler` class.
- **Game Mechanics**: Manages game logic, including piece dropping, line clearing, and game over conditions.

### Project Structure
- **Main Package (`main`)**:
  - `GamePanel.java`: Manages the game loop, rendering, and game state.
  - `KeyHandler.java`: Handles keyboard input for controlling the Tetris pieces.
  - `Main.java`: Entry point of the game.
  - `PlayManager.java`: Manages the gameplay logic, including piece generation and line clearing.
  - `Sound.java`: Handles music and sound effects.
- **Mino Package (`mino`)**:
  - `Block.java`: Basic building block for all mino types.
  - `Mino.java`: Abstract class representing the general structure of a Tetris piece.
  - Specific Mino Classes:
    - `Mino_Bar.java`
    - `Mino_L1.java`
    - `Mino_L2.java`
    - `Mino_Square.java`
    - `Mino_T.java`
    - `Mino_Z1.java`
    - `Mino_Z2.java`
  
### Setup
- Ensure Java SE 17 is installed on your system.
- Clone or download the project to your local machine.
- Compile and run the `Main.java` class to start the game.

### Technologies Used
This project is developed using Java SE 17, showcasing object-oriented programming practices, and graphical user interface development with Swing.

### Contributor
This Tetris game was developed independently as a personal project to deepen my understanding of Java and game development principles.

## Version Française

### Introduction
Ce projet personnel est une implémentation en Java 17 du jeu classique Tetris. Développé indépendamment à la maison pour l'exercice, il présente une interface graphique utilisateur, des effets sonores de jeu, de la musique, et diverses pièces de Tetris connues sous le nom de "minos". L'architecture du projet englobe une variété de classes pour gérer les mécaniques de jeu, les interactions utilisateur, et le rendu graphique.

### Caractéristiques Clés
- **Interface Graphique Utilisateur** : Utilise Java Swing pour le rendu du plateau de jeu, l'aperçu de la prochaine pièce et l'affichage des scores.
- **Effets Sonores et Musique** : Intègre de la musique de fond et des effets sonores pour les lignes complétées et la fin du jeu en utilisant la classe `Sound`.
- **Système de Minos Versatile** : Comprend plusieurs classes de minos, telles que `Mino_Bar`, `Mino_Square`, et `Mino_T`, représentant différents pièces de Tetris.
- **Gestion des Entrées Utilisateur** : Traite les entrées du clavier pour le mouvement et la rotation des pièces à travers la classe `KeyHandler`.
- **Mécaniques de Jeu** : Gère la logique de jeu, y compris la chute des pièces, l'effacement des lignes, et les conditions de fin de jeu.

### Structure du Projet
- **Package Principal (`main`)** :
  - `GamePanel.java` : Gère la boucle de jeu, le rendu, et l'état du jeu.
  - `KeyHandler.java` : Gère les entrées du clavier pour contrôler les pièces de Tetris.
  - `Main.java` : Point d'entrée du jeu.
  - `PlayManager.java` : Gère la logique de jeu, y compris la génération des pièces et l'effacement des lignes.
  - `Sound.java` : Gère la musique et les effets sonores.
- **Package Mino (`mino`)** :
  - `Block.java` : Bloc de base pour tous les types de minos.
  - `Mino.java` : Classe abstraite représentant la structure générale d'une pièce de Tetris.
  - Classes de Minos Spécifiques :
    - `Mino_Bar.java`
    - `Mino_L1.java`
    - `Mino_L2.java`
    - `Mino_Square.java`
    - `Mino_T.java`
    - `Mino_Z1.java`
    - `Mino_Z2.java`

### Configuration
- Assurez-vous que Java SE 17 est installé sur votre système.
- Clonez ou téléchargez le projet sur votre machine locale.
- Compilez et exécutez la classe `Main.java` pour démarrer le jeu.

### Technologies Utilisées
Ce projet est développé avec Java SE 17, mettant en avant les pratiques de programmation orientée objet et le développement d'interface graphique utilisateur avec Swing.

### Contributeurs
Ce jeu Tetris a été développé indépendamment comme un projet personnel pour approfondir ma compréhension de Java et des principes de développement de jeu.
