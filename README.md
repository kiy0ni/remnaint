# RemnA.I.nt

Un jeu vidéo *top-down shooter* 2D développé en Python avec la bibliothèque Pygame. Il s'agit de notre projet de fin d'année pour la spécialité NSI (Terminale).

![Menu Principal de Remnaint](https://imgur.com/bvVfyfd)
![Gameplay de Remnaint](https://imgur.com/ta3auxH)

*(Remarque : Pour que les images ci-dessus s'affichent, vous devez les héberger quelque part, par exemple en les glissant dans une "Issue" GitHub pour générer un lien, puis remplacer les URL `imgur.com`.)*

---

## Installation

Pour jouer au jeu, vous avez besoin de Python 3 et de Pygame.

1.  Clonez ce dépôt sur votre machine locale :
    ```bash
    git clone [https://github.com/KiyOni/Remnaint.git](https://github.com/KiyOni/Remnaint.git)
    ```

2.  Accédez au dossier du projet :
    ```bash
    cd Remnaint
    ```

3.  Installez les dépendances (principalement Pygame) :
    ```bash
    pip install -r requirements.txt
    ```
    *(Vous devrez créer le fichier `requirements.txt` - voir instructions plus bas).*

## Comment Jouer

Une fois les dépendances installées, lancez le jeu en exécutant le fichier `main.py` :

```bash
python main.py
````

### Contrôles

  * **Clavier/Souris :** ZQSD (ou WASD) pour bouger, Souris pour viser, Clic gauche pour tirer.
  * **Manette :** Le jeu prend également en charge la manette.

-----

## Fonctionnalités

  * Système de combat dynamique (joueur et ennemis).
  * Menus complets (principal, pause, options avec gestion du volume).
  * Musique et effets sonores.
  * Prise en charge de la manette en plus du clavier/souris.
  * Système de sauvegarde de la progression (`save_manager.py`).

## 🛠️ Technologies Utilisées

  * **Langage :** Python 3
  * **Bibliothèque principale :** Pygame

-----

## L'Équipe

Ce projet a été réalisé par une équipe de trois développeurs :

  * **Sacha (KiyOni)** : Structure principale du code, gestion des menus, musique, code du joueur et documentation.
  * **Mathias** : Développement de l'IA des ennemis et gestion de la carte.
  * **Eloi** : Création des *pixel arts* (design et animations).

## Licence

Ce projet est publié sous la **Licence MIT**. Voir le fichier `LICENSE` pour plus de détails.
